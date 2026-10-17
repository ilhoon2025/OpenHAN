# Set default language to Korean on first run

이 문서는 OpenHAN 데스크톱 앱( Electron + React )에서 "처음 실행 시 기본 언어를 한국어(ko)로 설정"하는 방법을 안내합니다.

요약
- 앱이 최초 실행될 때 로컬 설정(예: electron-store)에 저장된 언어 설정이 없으면 `ko`를 기본값으로 저장합니다.
- 이후에는 사용자가 선택한 언어를 우선 사용합니다.

적용 시나리오(권장 구현)
1. 메인 프로세스에서 사용자의 언어 설정을 관리합니다. (예: `electron-store` 사용)
2. 렌더러(React)에서 i18n 초기화 시 메인 프로세스에서 전달한 언어를 기본값으로 사용합니다.
3. 설정 화면에서 언어를 변경하면 저장하고 재시작 또는 즉시 반영합니다.

샘플 구현 (JavaScript, Electron)

1) deps 설치
- 프로젝트 루트에서
  npm install electron-store i18next electron-ipc-main electron-ipc-renderer

2) 메인 프로세스 (main.js 또는 main.ts)

```js
// main.js (예시)
const { app, BrowserWindow, ipcMain } = require('electron');
const Store = require('electron-store');

const store = new Store({
  name: 'settings'
});

function createWindow() {
  const mainWindow = new BrowserWindow({
    width: 1200,
    height: 800,
    webPreferences: {
      nodeIntegration: false,
      contextIsolation: true,
      preload: path.join(__dirname, 'preload.js')
    }
  });

  mainWindow.loadURL(/* your app url */);
}

app.whenReady().then(() => {
  // 처음 실행인지 확인하고 locale 기본값을 설정합니다.
  // 저장된 값이 없으면 'ko'로 설정합니다.
  const locale = store.get('locale');
  if (!locale) {
    store.set('locale', 'ko');
    console.log('Locale not found — defaulting to ko');
  }

  createWindow();

  app.on('activate', function () {
    if (BrowserWindow.getAllWindows().length === 0) createWindow();
  });
});

// 렌더러에서 언어를 요청할 때 응답합니다.
ipcMain.handle('get-locale', () => {
  return store.get('locale');
});

// 언어 변경 요청을 받으면 저장합니다.
ipcMain.handle('set-locale', (event, value) => {
  store.set('locale', value);
  return true;
});
```

3) preload.js
- 안전한 IPC 브리지에서 렌더러가 로케일을 조회/설정하도록 제공합니다.

```js
const { contextBridge, ipcRenderer } = require('electron');

contextBridge.exposeInMainWorld('electronAPI', {
  getLocale: () => ipcRenderer.invoke('get-locale'),
  setLocale: (value) => ipcRenderer.invoke('set-locale', value)
});
```

4) 렌더러 (React) — i18n 초기화 예시 (i18next)

```js
// i18n.js
import i18n from 'i18next';
import { initReactI18next } from 'react-i18next';

// 로컬 리소스 로딩 예시
import en from './locales/en.json';
import ko from './locales/ko.json';

async function initI18n() {
  // electron 환경에서 main 프로세스에 저장된 locale 가져오기
  const defaultLocale = window?.electronAPI ? await window.electronAPI.getLocale() : 'ko';

  await i18n
    .use(initReactI18next)
    .init({
      resources: {
        en: { translation: en },
        ko: { translation: ko }
      },
      lng: defaultLocale,
      fallbackLng: 'en',
      interpolation: { escapeValue: false }
    });
}

export default initI18n;
```

5) 언어 변경 (설정 UI)
```js
// 예: 사용자가 언어를 바꿀 때
async function onChangeLocale(lang) {
  if (window?.electronAPI) {
    await window.electronAPI.setLocale(lang);
  }
  i18n.changeLanguage(lang);
}
```

추가 고려사항
- 시스템 기본 언어를 감지해서 한국어로 기본값을 설정하고 싶다면, `app.getLocale()` 또는 `app.getPreferredSystemLanguages()` 결과를 활용해 한국어(`ko`)를 우선 적용하도록 할 수 있습니다.

예시:
```js
const systemLocale = app.getLocale();
if (!store.get('locale')) {
  const isKorean = systemLocale && systemLocale.startsWith('ko');
  store.set('locale', isKorean ? 'ko' : 'ko'); // 여기서는 항상 ko로 설정하되 시스템 언어를 참고할 수 있음
}
```

패키지화된 배포(실행파일) 주의
- 이미 빌드된 OpenHAN.exe(바이너리)에는 이 변경을 반영할 수 없습니다. 소스 코드가 있어야 변경이 가능하므로, 앱 소스가 없다면 위 가이드를 개발자에게 적용해 다시 빌드해야 합니다.

제가 할 수 있는 일
- 위 코드를 그대로 저장소에 문서로 추가했습니다. (docs/SET_DEFAULT_LANGUAGE.md)
- 소스가 저장소에 이미 존재하면 메인 프로세스 파일에 직접 패치(커밋)하거나 PR을 생성해 드릴 수 있습니다.

이제 다음을 진행할까요?
- [A] 저장소에 이 문서 추가(이미 추가됨)
- [B] 저장소에 소스가 올라와 있으면 자동으로 패치해서 기본 언어 설정 구현
- [C] 아직 소스가 없다면, 이 문서를 바탕으로 소스 제공 후 제가 패치 진행

원하시는 옵션을 알려 주세요.