# 📝 OpenHAN **v2.6.0** · **_정식 릴리즈_** · 🌐 AI 웹 검색 · 🗂️ 내 PC 파일

✨ **HWP/HWPX 편집부터 AI 비서·맞춤법·공문서체 변환, AI 누끼 따기까지 — PC와 휴대폰에서.**

🇰🇷 **100% 한국인이 직접 기획하고 개발한 국산 오픈소스 워드프로세서입니다.**

<p align="center">
  <img src="https://raw.githubusercontent.com/ilhoon2025/OpenHAN/main/docs/images/logo-2010.png" width="64" alt="2010 로고">&nbsp;
  <img src="https://raw.githubusercontent.com/ilhoon2025/OpenHAN/main/docs/images/logo-2018.png" width="64" alt="2018 로고">&nbsp;
  <img src="https://raw.githubusercontent.com/ilhoon2025/OpenHAN/main/docs/images/logo-2024.png" width="64" alt="2024 로고">
</p>

### 📥 다운로드

| 플랫폼 | 파일 | 안내 |
| :--- | :--- | :--- |
| 🪟 **Windows 설치** | [`OpenHAN-2.6.0-Setup.exe`](https://github.com/ilhoon2025/OpenHAN/releases/download/v2.6.0/OpenHAN-2.6.0-Setup.exe) | 설치 위치를 고르면 시작 메뉴·바탕화면 바로가기가 생깁니다 **(추천)** |
| 🪟 **Windows 포터블** | [`OpenHAN-2.6.0-Portable.exe`](https://github.com/ilhoon2025/OpenHAN/releases/download/v2.6.0/OpenHAN-2.6.0-Portable.exe) | 설치 없이 파일 하나로 바로 실행 |
| 🤖 **Android** | [`OpenHAN-2.6.0-Android.apk`](https://github.com/ilhoon2025/OpenHAN/releases/download/v2.6.0/OpenHAN-2.6.0-Android.apk) | 휴대폰으로 옮겨 설치 (출처를 알 수 없는 앱 설치 허용 필요) |
| 🍎 **macOS (Apple 실리콘)** | [`OpenHAN-2.6.0-mac-arm64.dmg`](https://github.com/ilhoon2025/OpenHAN/releases/download/v2.6.0/OpenHAN-2.6.0-mac-arm64.dmg) | M1~M4 Mac |
| 🍎 **macOS (Intel)** | [`OpenHAN-2.6.0-mac-x64.dmg`](https://github.com/ilhoon2025/OpenHAN/releases/download/v2.6.0/OpenHAN-2.6.0-mac-x64.dmg) | Intel Mac · `.zip`도 함께 제공 |

> ⚠️ 코드 서명 인증서가 없는 무료 프로그램이라 처음 실행할 때 **Windows SmartScreen** 경고가 뜰 수 있습니다. **추가 정보 → 실행**을 누르세요.
>
> 🍎 macOS용은 Apple 공증을 받지 않아 처음 열 때 "확인되지 않은 개발자" 경고가 뜹니다. 앱을 **우클릭 → 열기**를 누르거나, 터미널에서 `xattr -cr /Applications/OpenHAN.app`을 실행하세요.

### 🆕 v2.6.0에서 바뀐 점

🌐 **AI 웹 검색** — AI가 필요하면 스스로 웹을 검색하고 페이지를 읽어 답합니다. 링크를 붙여 넣으면 그 페이지를 읽고, 답 아래에 출처가 붙습니다. 입력창의 **웹 검색**을 켜면 질문마다 먼저 찾아봅니다. (키 필요 없음)

📎 **무엇이든 첨부** — 사진(AI가 직접 봄) · 코드 · PDF · 워드 · 엑셀 · 파워포인트 · 한글 · ZIP · 동영상(장면 몇 장)을 올리면 AI가 읽습니다. 끌어다 놓기·붙여넣기도 됩니다. 답의 코드·표·목록도 보기 좋게 보입니다.

🖼️ **웹 사진 찾아 넣기 · 그림 만들기** — "○○ 사진 넣어 줘"라고 하면 후보 사진을 직접 보고 골라 문서에 넣고 출처·라이선스 캡션을 붙입니다. 알맞은 사진이 없거나 "그려 줘"라고 하면 그림을 만들어 넣습니다.

<p align="center">
  <img src="https://raw.githubusercontent.com/ilhoon2025/OpenHAN/main/docs/images/ai-photo.png" alt="AI가 웹 사진을 찾아 넣은 화면" width="680">
</p>

🧰 **앱의 모든 도구를 AI가** — 표 칸 합치기·행 추가·칸 색, 그림 크기·누끼 따기(창 없이 바로), 서식으로 새 문서, 링크 넣기 등 앱 기능 130여 개를 말로 시킬 수 있습니다.

🗂️ **내 컴퓨터 파일 (선택, 기본값 꺼짐)** — 입력창의 🗂 버튼에서 **끔 / 읽기만 / 읽기·쓰기**를 고릅니다. 켜면 AI가 PC 파일을 찾고 읽고, 저장·복사·옮기기·이름 바꾸기·휴지통으로 버리기까지 합니다. 허용 폴더를 정할 수 있고, 바꾸기 전에 매번 확인 창이 뜨며(기본), 시스템 폴더·AppData·.ssh·실행 파일은 항상 막혀 있습니다.

<p align="center">
  <img src="https://raw.githubusercontent.com/ilhoon2025/OpenHAN/main/docs/images/ai-pc-access.png" alt="내 컴퓨터 파일 접근 설정" width="340">
</p>

💬 **새 입력창** — 글 칸과 📎 · 웹 검색 · 내 PC 버튼, 보내기를 하나의 둥근 카드에 담았고, 글이 길어지면 칸이 늘어납니다.

### 🆕 v2.5.0에서 바뀐 점

🍎 **macOS 앱 정식 제공** — Apple 실리콘(arm64)과 Intel(x64) 빌드를 모두 제공합니다.

⌨️ **안드로이드 한글 입력 수정** — 휴대폰 키보드로 한글이 안 써지거나 글자가 겹치던 문제를 고쳤습니다. (조합 중 쪽 나눔·단축키·덮어쓰기 처리가 끼어들지 않도록 변경)

🔑 **Pollinations 키 내장** — OpenHAN 전용 Pollinations 키가 앱에 들어 있어서, 키를 따로 넣지 않아도 새 Pollinations 서버로 넉넉하게 AI를 씁니다. 원하면 **도구 → 환경 설정 → AI**에서 자기 키로 바꿀 수 있습니다.

### ✨ v2.0에서 추가된 기능

✨ **AI 비서** — "회의록 써 줘", "월별 예산 표 만들어 줘", "용지를 가로로 바꿔 줘"처럼 말하면 문서에 바로 실행합니다. (`Ctrl+K, A`)

<p align="center">
  <img src="https://raw.githubusercontent.com/ilhoon2025/OpenHAN/main/docs/images/ai-assistant.png" alt="AI 비서" width="680">
</p>

🔤 **맞춤법·띄어쓰기 인포그래픽** — 정확도 점수, 오류 유형별 막대, 고침 카드로 보여 주고 버튼 하나로 모두 고칩니다. (`F8` 검사 · `Ctrl+F8` 자동 수정)

<p align="center">
  <img src="https://raw.githubusercontent.com/ilhoon2025/OpenHAN/main/docs/images/ai-spell.png" alt="맞춤법 인포그래픽" width="680">
</p>

🏛️ **공문서 / 논문 투고 스타일 변환기** — 대충 쓴 글을 공문서체(~함, ~바람), 학술 논문체, 보고서체 등으로 바꾸고 원문과 나란히 비교합니다.

<p align="center">
  <img src="https://raw.githubusercontent.com/ilhoon2025/OpenHAN/main/docs/images/ai-style.png" alt="공문서체 변환" width="680">
</p>

📱 **HWP 요약 & 미디엄 뷰어** — 무거운 HWP를 열지 않고 한 줄 요약·핵심 내용·그림·표만 휴대폰 카드로 훑어봅니다. (`Ctrl+K, P`)

<p align="center">
  <img src="https://raw.githubusercontent.com/ilhoon2025/OpenHAN/main/docs/images/ai-cards.png" alt="요약 카드 뷰어" width="680">
</p>

🔑 **무료 AI 자동 전환** — Gemini · Groq · Mistral · Cerebras · OpenRouter의 무료 키를 넣어 두면 한도에 걸릴 때 다음 AI로 넘어갑니다. 키가 없어도 Pollinations로 바로 쓸 수 있고, 로컬 AI(Ollama)는 무제한·오프라인입니다. **도구 → 환경 설정 → AI**에 '무료 키 발급' 바로가기와 '연결 테스트'가 있습니다.

🤖 **안드로이드 앱** — 휴대폰 전용 화면(앱 바 · 아래 서식 줄 · 기능 시트), 공유 시트로 저장, 다른 앱에서 HWP를 OpenHAN으로 열기.

<p align="center">
  <img src="https://raw.githubusercontent.com/ilhoon2025/OpenHAN/main/docs/images/android-editor.png" alt="안드로이드 편집 화면" width="240">&nbsp;
  <img src="https://raw.githubusercontent.com/ilhoon2025/OpenHAN/main/docs/images/android-menu.png" alt="안드로이드 기능 시트" width="240">
</p>

🍎 **macOS 대응** — 신호등 창 단추, ⌘ 단축키, Finder에서 문서 열기

💿 **설치 파일과 기본 앱 설정** — Setup 설치 파일을 제공하고, hwp · hwpx · ohan · txt · html을 두 번 눌러 OpenHAN으로 열 수 있습니다.

🎨 **테마별 새 로고** — 2010 · 2018 · 2024 테마마다 다른 로고, 2018 테마의 사선 모서리 탭.

### 🛠️ 프로젝트 소개

🏷️ **이름:** OpenHAN  
💎 **버전:** 2.6.0  
🖥️ **플랫폼:** Windows x64 · Android · macOS  
🇰🇷 **개발:** 100% Korean-Developed · Made in Korea  
⚙️ **기반 기술:** Electron · Capacitor · React · Tiptap / ProseMirror  
🧠 **AI:** OpenAI 호환 API 자동 전환 · 내장 U²-Net 모델(ONNX Runtime, 로컬)  
📜 **프로젝트 라이선스:** MIT

### ✨ 기존 주요 기능

📄 **HWP · HWPX 지원:** HWP 5.0과 HWPX를 읽고 저장합니다. 저장한 파일을 한컴오피스 한글 2024에서 열어 글꼴·색·셀 배경·병합 표·그림·용지가 유지되는 것을 확인했습니다.

<p align="center">
  <img src="https://github.com/user-attachments/assets/0ce63e8e-4c1e-491f-93f0-04023a6eb852" alt="HWP HWPX 문서 지원" width="600">
</p>

🎨 **3가지 화면 테마:** **2010 · 2018 · 2024** — 처음 실행할 때 고르고 환경 설정에서 언제든 바꿀 수 있습니다. 어두운 화면도 지원합니다.

<p align="center">
  <img src="https://raw.githubusercontent.com/ilhoon2025/OpenHAN/main/docs/images/theme-2010.png" alt="2010 테마" width="680">
</p>

🗂️ **문서 탭 · 시작 화면:** 여러 문서를 탭으로 편집하고 12가지 서식으로 시작합니다.

✍️ **문서 편집:** 글자·문단 모양, 표(셀 합치기·나누기), 그림, 쪽 번호, 편집 용지(세로/가로·여백 프리셋)

🪄 **로컬 AI 누끼 따기:** 내장 AI 모델로 배경을 지우고 마술봉·지우개·복원 붓으로 다듬어 투명 PNG로 저장합니다. 인터넷 없이 동작합니다.

<p align="center">
  <img src="https://github.com/user-attachments/assets/8caf8011-5e00-4416-91d9-fd3d67e36aca" alt="OpenHAN AI 누끼 따기" width="680">
</p>

⌨️ **한글과 같은 단축키:** `Alt+L`, `Alt+T`, `Ctrl+N, T`, `Ctrl+Y`, `F5` 셀 블록 등 — **F1**로 전체 목록을 검색하세요.

### 📖 사용 방법

🚀 **실행:** `OpenHAN-2.6.0-Setup.exe`로 설치하거나 Portable을 바로 실행하세요.  
📂 **불러오기:** **Ctrl+O**로 문서를 선택하세요.  
✍️ **새 문서:** **Alt+N**을 누르거나 시작 화면에서 서식을 고르세요.  
✨ **AI 비서:** **Ctrl+K, A** — 맞춤법은 **F8**, 자동 수정은 **Ctrl+F8**  
🪄 **누끼 따기:** 그림을 선택하고 **Ctrl+Shift+K**를 누르세요.

<p align="center">
  <img src="https://github.com/user-attachments/assets/ba0257a6-8a48-4f24-98df-71ac05e10186" alt="AI 배경 제거 작업 화면" width="680">
</p>

💾 **저장:** **Ctrl+S**로 HWP, HWPX 또는 OHAN 형식을 선택하세요.

<p align="center">
  <img src="https://github.com/user-attachments/assets/2c353bab-ec23-4d5a-88be-7c5d10b587bc" alt="문서 저장 화면" width="560">
</p>

📤 **공유:** PDF로 내보내거나 **Ctrl+P**로 인쇄하세요.

<p align="center">
  <img src="https://github.com/user-attachments/assets/807cecc6-a92c-4e63-a45b-ea1d36a02cdb" alt="문서 편집 및 인쇄" width="680">
</p>

### 📌 문서 형식 · AI 안내

HWP 3.0 이하, 암호가 설정된 HWP, 배포용 HWP 문서는 지원하지 않습니다. 머리말/꼬리말·각주·도형·표 캡션은 아직 읽거나 쓰지 않으며, HWP/HWPX 저장 시 일부 OpenHAN 전용 서식이 단순화되므로 모든 서식을 유지하려면 **OHAN**을 사용하세요.

AI 기능을 쓸 때만 해당 글이 그 순간 사용한 AI 제공처로 전달되고, API 키는 컴퓨터 계정의 암호화 저장소에 보관됩니다. 키 없이 쓰는 무료 AI는 요청 간격 제한이 있어 품질이 들쭉날쭉할 수 있으니, Gemini나 Groq 무료 키를 하나 넣는 것을 추천합니다.

<p align="center">
  <img src="https://github.com/user-attachments/assets/98ac6bd4-d6b0-4bd9-8d46-65df27258262" alt="문서 형식 안내" width="600">
</p>

### ✉️ 문의 및 피드백

🐞 오류는 앱 버전, 플랫폼, 재현 순서를 함께 적어 **GitHub Issues**에 남겨 주세요.  
💡 새로운 기능 제안과 개선 의견도 환영합니다.

🇰🇷 **Proudly Made in Korea · 100% Korean-Developed**

📝 *당신의 글, 당신의 작업 공간. OpenHAN.*

<p align="center">
  <img src="https://github.com/user-attachments/assets/edc61526-ba9d-4725-8f06-938f891363a9" alt="OpenHAN 프로젝트" width="420">
</p>
