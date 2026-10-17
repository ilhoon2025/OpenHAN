# 📝 OpenHAN (한국어)

### 친숙한 글쓰기, 더 많은 가능성.

**HWP/HWPX 지원과 로컬 AI 누끼(배경 제거)를 갖춘 Windows용 한글 워드프로세서입니다.**

🪟 Windows x64 · 💎 v2.0.0 · 🎨 3가지 인터페이스 테마 · 📜 MIT

[English · README](README.en.md)

OpenHAN은 문서 편집, 표, 이미지, 그리고 페이지 레이아웃을 하나의 데스크톱 작업공간으로 제공합니다.

기존 문서를 열거나 템플릿으로 시작하고, 편한 인터페이스를 선택하세요.

---

## ✨ 주요 기능

### 📄 HWP & HWPX 읽기/쓰기

HWP 5.0과 HWPX 문서를 열고 저장할 수 있으며, OpenHAN 고유 포맷 `.ohan`으로 에디터 형식을 보존할 수 있습니다.

<p align="center">
  <img src="https://github.com/user-attachments/assets/0ce63e8e-4c1e-491f-93f0-04023a6eb852" alt="OpenHAN 문서 지원" width="600">
</p>

### 🎨 3가지 인터페이스 테마

**2010**, **2018**, **2024** 테마 중 선택할 수 있습니다. 문서 페이지는 흰색으로 유지하면서 다크 테마를 사용할 수 있습니다.

### 🗂️ 탭형 문서 작업

여러 문서를 탭으로 열고 최근 파일을 빠르게 불러오며, 추가 창도 열 수 있습니다.

### ✍️ 풍부한 텍스트 서식

글꼴, 크기, 색상, 자간, 줄간격, 단락 정렬 및 들여쓰기 등을 조절하고, 제목, 목록, 서식 복사를 사용할 수 있습니다.

### 📊 표 편집

표 삽입, 행·열 추가 및 삭제, 셀 병합과 분할을 지원합니다.

### 🖼️ 이미지 및 AI 배경 제거

ONNX Runtime으로 로컬에서 실행되는 U²-Net 모델을 이용해 이미지 배경을 제거합니다.

매직 완드, 지우개, 복원 브러시로 결과를 다듬고 문서에 삽입하거나 투명 PNG로 저장할 수 있습니다.

<p align="center">
  <img src="https://github.com/user-attachments/assets/8caf8011-5e00-4416-91d9-fd3d67e36aca" alt="OpenHAN AI 배경 제거 기능" width="680">
</p>

### 📐 페이지 레이아웃 제어

용지 크기, 방향, 여백, 쪽 나누기 및 쪽 번호를 설정하고 자와 줌으로 보기를 조절할 수 있습니다.

### 📤 내보내기 및 인쇄

PDF, HTML, TXT로 내보내기하고 데스크톱 인쇄 대화상자를 통해 인쇄할 수 있습니다.

### 📋 내장 템플릿

가계부, 주간 플래너, 회의록, 상장 템플릿 등으로 빠르게 시작할 수 있습니다.

### ⌨️ 단축키 중심 편집

찾기/바꾸기, 서식 복사 등 다양한 단축키를 지원하며, `F1`을 눌러 단축키 참조를 열 수 있습니다.

---

## 📥 다운로드 및 실행

릴리스 페이지에서 Windows ZIP 파일을 다운로드하세요.

### STEP 01. ZIP 파일 압축 해제

다운로드한 ZIP 파일의 압축을 풉니다.

<p align="center">
  <img src="https://github.com/user-attachments/assets/8345dcef-ae43-4cf2-8c37-ebca27c15f8f" alt="ZIP 압축 해제" width="600">
</p>

### STEP 02. 프로그램 폴더 열기

압축을 해제한 폴더에서 `win-unpacked` 폴더를 엽니다.

<p align="center">
  <img src="https://github.com/user-attachments/assets/c9cf906f-8436-48a4-91f6-8d5bee9faeaa" alt="OpenHAN 프로그램 폴더" width="680">
</p>

### STEP 03. OpenHAN 실행

`OpenHAN.exe` 파일을 더블클릭하여 실행합니다.

<p align="center">
  <img src="https://github.com/user-attachments/assets/16a9f387-3eaf-4fc6-9787-7af3d7c64ffb" alt="OpenHAN 실행 파일" width="680">
</p>

> **주의:** 실행 파일, DLL, `resources` 폴더를 함께 유지해야 합니다. 현재 ZIP 배포판은 별도의 설치 프로그램이 필요하지 않으며, 설정은 Windows 사용자 프로필에 저장됩니다.

---

## 📖 빠른 시작

### 1. 🆕 새 문서 만들기

템플릿을 선택하거나 `Alt+N`을 눌러 빈 문서를 만듭니다.

### 2. 📂 문서 열기

`Ctrl+O`로 HWP, HWPX, OHAN, TXT, HTML 파일을 엽니다.

### 3. ✍️ 문서 편집하기

서식 도구로 텍스트를 꾸미고 표나 이미지를 추가합니다.

### 4. 🪄 AI 이미지 배경 제거

이미지를 선택하고 `Ctrl+Shift+K`를 실행합니다.

배경 제거 결과를 다듬은 뒤 문서에 적용하거나 투명 PNG로 저장할 수 있습니다.

<p align="center">
  <img src="https://github.com/user-attachments/assets/ba0257a6-8a48-4f24-98df-71ac05e10186" alt="AI 이미지 배경 제거 작업" width="680">
</p>

### 5. 💾 문서 저장하기

`Ctrl+S`를 눌러 HWP, HWPX, OHAN 중 원하는 형식으로 저장합니다.

<p align="center">
  <img src="https://github.com/user-attachments/assets/2c353bab-ec23-4d5a-88be-7c5d10b587bc" alt="문서 저장 화면" width="560">
</p>

### 6. 📤 공유 및 인쇄하기

파일 메뉴에서 PDF로 내보내거나 `Ctrl+P`를 눌러 인쇄합니다.

<p align="center">
  <img src="https://github.com/user-attachments/assets/807cecc6-a92c-4e63-a45b-ea1d36a02cdb" alt="OpenHAN 문서 편집 및 인쇄" width="680">
</p>

### 7. 🎨 테마 및 환경 설정

**도구 → 환경 설정**에서 인터페이스 테마와 기타 옵션을 변경합니다.

---

## 📁 지원 포맷

| 형식 | 열기 | 저장 / 내보내기 |
| :--- | :---: | :---: |
| HWP 5.0 (`.hwp`) | ✅ | ✅ |
| HWPX (`.hwpx`) | ✅ | ✅ |
| OpenHAN (`.ohan`) | ✅ | ✅ |
| 일반 텍스트 (`.txt`) | ✅ | ✅ 내보내기 |
| HTML (`.html`, `.htm`) | ✅ | ✅ 내보내기 |
| PDF (`.pdf`) | — | ✅ 내보내기 |

**호환성 안내**

HWP 3.0 이하, 암호로 보호된 HWP, 배포 보호된 HWP는 지원하지 않습니다.

일부 OpenHAN 전용 서식(예: 글머리표, 블록 인용)은 HWP/HWPX로 저장할 때 일반 단락으로 변환될 수 있습니다.

OpenHAN 고유 서식을 보존하려면 **OHAN 형식**을 사용하세요.

<p align="center">
  <img src="https://github.com/user-attachments/assets/98ac6bd4-d6b0-4bd9-8d46-65df27258262" alt="OpenHAN 문서 호환성" width="600">
</p>

---

## ⌨️ 유용한 단축키

| 동작 | 단축키 |
| :--- | :--- |
| 🆕 새 문서 | `Alt+N` |
| 📂 파일 열기 | `Ctrl+O` |
| 💾 저장 | `Ctrl+S` |
| 🖨️ 인쇄 | `Ctrl+P` |
| 🔎 찾기 / 바꾸기 | `Ctrl+F` / `Ctrl+H` |
| ✍️ 문자 / 단락 서식 | `Alt+L` / `Alt+T` |
| 📐 페이지 설정 | `F7` |
| 🪄 이미지 배경 제거 | `Ctrl+Shift+K` |
| 🖥️ 전체화면 | `F11` |
| ❓ 단축키 참조 | `F1` |

---

## 🛠️ 사용 기술

OpenHAN은 다음 기술을 기반으로 개발되었습니다.

| 분야 | 기술 |
| :--- | :--- |
| 데스크톱 애플리케이션 | Electron |
| 사용자 인터페이스 | React |
| 문서 편집 엔진 | Tiptap / ProseMirror |
| AI 배경 제거 | U²-Net |
| 로컬 AI 추론 | ONNX Runtime |
| 파일 처리 | fflate / cfb |

---

## ✉️ 지원 및 버그 제보

사용 중 문제가 발생하면 GitHub 저장소의 **Issues** 탭에 보고해 주세요.

원활한 문제 해결을 위해 다음 정보를 포함해 주세요.

- OpenHAN 버전
- Windows 버전
- 문제 재현 단계
- 기대한 결과와 실제 동작

문서 호환성 문제는 개인정보를 제거한 예제 파일을 첨부해 주세요.

---

## 📜 라이선스 & 크레딧

OpenHAN 패키지는 **MIT 라이선스**를 선언합니다.

번들된 타사 구성요소는 각각의 라이선스를 유지합니다.

| 구성요소 | 라이선스 |
| :--- | :--- |
| OpenHAN | MIT |
| U²-Net | Apache-2.0 |
| cfb | Apache-2.0 |
| ONNX Runtime | MIT |
| Tiptap / ProseMirror | MIT |
| fflate | MIT |

<p align="center">
  <img src="https://github.com/user-attachments/assets/edc61526-ba9d-4725-8f06-938f891363a9" alt="OpenHAN 라이선스 및 크레딧" width="420">
</p>

---

<div align="center">

### 📝 OpenHAN

**당신의 말, 당신의 작업 공간.**

친숙한 글쓰기, 더 많은 가능성.

**Windows x64 · Version 2.0.0 · Open Source**

</div>
