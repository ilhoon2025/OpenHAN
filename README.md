# 📝 OpenHAN (한국어)

### 친숙한 글쓰기, 더 많은 가능성.

**HWP/HWPX 지원과 로컬 AI 누끼(배경 제거)를 갖춘 Windows용 한글 워드프로세서입니다.**

🪟 Windows x64 · 💎 v2.0.0 · 🎨 3가지 인터페이스 테마 · 📜 MIT

[English · README](README.en.md)

OpenHAN은 문서 편집, 표, 이미지, 그리고 페이지 레이아웃을 하나의 데스크톱 작업공간으로 제공합니다. 기존 문서를 열거나 템플릿으로 시작하고, 편한 인터페이스를 선택하세요.

## ✨ 주요 기능

- 📄 **HWP & HWPX 읽기/쓰기** — HWP 5.0과 HWPX 문서를 열고 저장할 수 있으며, OpenHAN 고유 포맷 `.ohan`으로 에디터 형식을 보존할 수 있습니다.
- 
<img width="785" height="94" alt="image" src="https://github.com/user-attachments/assets/0ce63e8e-4c1e-491f-93f0-04023a6eb852" />
- 
- 🎨 **3가지 인터페이스 테마** — **2010**, **2018**, **2024** 테마 중 선택하십시오. 문서 페이지는 흰색으로 유지하면서 다크 테마를 사용할 수 있습니다.
- 🗂️ **탭형 문서 작업** — 여러 문서를 탭으로 열고 최근 파일을 빠르게 불러오며, 추가 창도 열 수 있습니다.
- ✍️ **풍부한 텍스트 서식** — 글꼴, 크기, 색상, 자간, 줄간격, 단락 정렬 및 들여쓰기 등을 조절하고, 제목, 목록, 서식 복사를 사용할 수 있습니다.
- 📊 **표 편집** — 표 삽입, 행·열 추가/삭제, 셀 병합 및 분할을 지원합니다.
- 🖼️ **이미지 및 AI 배경 제거** — ONNX Runtime으로 로컬에서 실행되는 U²-Net 모델로 배경을 제거합니다. 매직 완드, 지우개, 복원 브러시로 결과를 다듬고 문서에 삽입하거나 투명 PNG로 저장할 수 있습니다.
- 
<img width="1378" height="894" alt="image" src="https://github.com/user-attachments/assets/8caf8011-5e00-4416-91d9-fd3d67e36aca" />
- 
- 📐 **페이지 레이아웃 제어** — 용지 크기, 방향, 여백, 쪽 나누기 및 쪽 번호를 설정하고 자와 줌으로 보기를 조절하세요.
- 📤 **내보내기 및 인쇄** — PDF, HTML, TXT로 내보내기하고, 데스크톱 인쇄 대화상자를 통해 인쇄할 수 있습니다.
- 📋 **내장 템플릿** — 가계부, 주간 플래너, 회의록, 상장 템플릿 등으로 빠르게 시작할 수 있습니다.
- ⌨️ **단축키 중심 편집** — 찾기/바꾸기, 서식 복사, F1로 단축키 참조를 열 수 있습니다.

## 📥 다운로드 및 실행

릴리스 페이지의 Windows ZIP 파일을 다운로드하세요.

1. ZIP 압축을 풀고 전체 폴더를 유지합니다.

<img width="1149" height="648" alt="image" src="https://github.com/user-attachments/assets/8345dcef-ae43-4cf2-8c37-ebca27c15f8f" />

2. `win-unpacked` 폴더를 엽니다.

<img width="1920" height="511" alt="image" src="https://github.com/user-attachments/assets/c9cf906f-8436-48a4-91f6-8d5bee9faeaa" />

3. `OpenHAN.exe`를 실행합니다.

<img width="1917" height="512" alt="image" src="https://github.com/user-attachments/assets/16a9f387-3eaf-4fc6-9787-7af3d7c64ffb" />

실행 파일, DLL, 그리고 `resources` 폴더를 함께 두어야 합니다. 설치 프로그램은 필요하지 않으며 설정은 Windows 사용자 프로필에 저장됩니다.

## 📖 빠른 시작

1. 🆕 새 문서: 템플릿을 선택하거나 `Alt+N`으로 빈 문서 생성
2. 📂 파일 열기: `Ctrl+O`로 HWP/HWPX/OHAN/TXT/HTML 파일 열기
3. ✍️ 편집: 서식 도구로 텍스트를 스타일링하고 표나 이미지를 추가
4. 🪄 이미지 누끼 따기: 이미지를 선택하고 `Ctrl+Shift+K` 실행 후 결과를 다듬고 적용

<img width="1378" height="894" alt="image" src="https://github.com/user-attachments/assets/ba0257a6-8a48-4f24-98df-71ac05e10186" />

6. 💾 저장: `Ctrl+S`로 HWP, HWPX, OHAN 중 선택하여 저장

<img width="821" height="550" alt="image" src="https://github.com/user-attachments/assets/2c353bab-ec23-4d5a-88be-7c5d10b587bc" />

8. 📤 공유: 파일 메뉴에서 PDF로 내보내거나 `Ctrl+P`로 인쇄

<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/807cecc6-a92c-4e63-a45b-ea1d36a02cdb" />

10. 🎨 설정 변경: 도구 → 환경 설정에서 테마와 기타 옵션 조정

## 📁 지원 포맷

| 형식 | 열기 | 저장 / 내보내기 |
| --- | --- | --- |
| HWP 5.0 (`.hwp`) | ✅ | ✅ |
| HWPX (`.hwpx`) | ✅ | ✅ |
| OpenHAN (`.ohan`) | ✅ | ✅ |
| 일반 텍스트 (`.txt`) | ✅ | ✅ 내보내기 |
| HTML (`.html`, `.htm`) | ✅ | ✅ `.html`로 내보내기 |
| PDF (`.pdf`) | — | ✅ 내보내기 |

HWP 3.0 이하,암호로 보호된 HWP, 배포 보호된 HWP는 지원하지 않습니다. 일부 OpenHAN 전용 서식(예: 글머리표, 블록 인용)은 HWP/HWPX로 저장할 때 일반 단락으로 변환될 수 있습니다. OpenHAN 고유 서식을 보존하려면 **OHAN**을 사용하세요.

<img width="785" height="94" alt="image" src="https://github.com/user-attachments/assets/98ac6bd4-d6b0-4bd9-8d46-65df27258262" />


## ⌨️ 유용한 단축키

| 동작 | 단축키 |
| --- | --- |
| 새 문서 | `Alt+N` |
| 열기 | `Ctrl+O` |
| 저장 | `Ctrl+S` |
| 인쇄 | `Ctrl+P` |
| 찾기/바꾸기 | `Ctrl+F` / `Ctrl+H` |
| 문자/단락 서식 | `Alt+L` / `Alt+T` |
| 페이지 설정 | `F7` |
| 이미지 배경 제거 | `Ctrl+Shift+K` |
| 전체화면 | `F11` |
| 단축키 참조 | `F1` |

## 🛠️ 사용 기술

Electron · React · Tiptap / ProseMirror · U²-Net · ONNX Runtime · fflate · cfb

## ✉️ 지원

버그는 저장소의 Issues 탭에 보고해 주세요. OpenHAN 버전, Windows 버전, 재현 단계, 기대 결과를 포함해 주시면 빠르게 확인할 수 있습니다. 문서 호환성 문제는 개인 정보를 제거한 예제 파일을 첨부해 주세요.

## 📜 라이선스 & 크레딧

OpenHAN 패키지는 **MIT 라이선스**를 선언합니다. 번들된 타사 구성요소는 각자 라이선스를 유지합니다 (예: U²-Net 및 cfb는 Apache-2.0, ONNX Runtime·Tiptap/ProseMirror·fflate는 MIT).

<img width="567" height="420" alt="image" src="https://github.com/user-attachments/assets/edc61526-ba9d-4725-8f06-938f891363a9" />

---

📝 *당신의 말, 당신의 작업 공간. OpenHAN.*
