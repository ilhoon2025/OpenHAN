# 📝 OpenHAN (English)

### 🇰🇷 A 100% Korean-Developed Word Processor

**Familiar Writing. More Possibilities.**

**A Windows word processor featuring HWP/HWPX compatibility and AI-powered background removal that runs locally on your computer.**

🪟 Windows x64 · 💎 v2.0.0 · 🇰🇷 Made in Korea · 🎨 3 Interface Themes · 📜 MIT License

[🇰🇷 한국어 · README](README.md)

---

## 🇰🇷 Proudly Made in Korea

### A New Document Editing Experience, Born in South Korea

**OpenHAN is an open-source word processor entirely conceived and developed by Korean developers.**

Designed with the document-editing needs of Korean users in mind, OpenHAN aims to provide an intuitive, powerful, and accessible writing experience for everyone.

From editing HWP/HWPX documents to removing image backgrounds using local AI, OpenHAN brings essential document-editing capabilities together in one desktop workspace.

**Developed in Korea. Open to Everyone.**

---

## ✨ Key Features

### 📄 HWP & HWPX Support

Open, edit, and save HWP 5.0 and HWPX documents.

Use OpenHAN's native `.ohan` format to preserve editor-specific formatting and document structure.

<p align="center">
  <img src="https://github.com/user-attachments/assets/0ce63e8e-4c1e-491f-93f0-04023a6eb852" alt="OpenHAN Document Format Support" width="600">
</p>

### 🎨 Three Interface Themes

Choose from three distinctive interface themes: **2010**, **2018**, and **2024**.

Enjoy a dark interface while keeping document pages white for comfortable editing.

### 🗂️ Tabbed Document Workspace

Open multiple documents in tabs, quickly access recent files, and launch additional windows when needed.

### ✍️ Rich Text Formatting

Customize fonts, sizes, colors, character spacing, line spacing, paragraph alignment, and indentation.

Additional features include headings, lists, and format painting.

### 📊 Table Editing

Insert tables, add or remove rows and columns, and merge or split cells.

### 🖼️ Images & AI Background Removal

Remove image backgrounds locally using the **U²-Net model powered by ONNX Runtime**.

Refine the results with Magic Wand, Eraser, and Restore Brush tools.

Insert the processed image directly into your document or export it as a transparent PNG.

**AI background removal runs locally on your computer.**

<p align="center">
  <img src="https://github.com/user-attachments/assets/8caf8011-5e00-4416-91d9-fd3d67e36aca" alt="OpenHAN AI Background Removal" width="680">
</p>

### 📐 Page Layout Controls

Configure paper size, orientation, margins, page breaks, and page numbers.

Use rulers and zoom controls to fine-tune your document layout.

### 📤 Export & Printing

Export documents to PDF, HTML, and TXT formats.

Print directly using the native Windows print dialog.

### 📋 Built-in Templates

Get started quickly with templates for budgets, weekly planners, meeting minutes, certificates, and more.

### ⌨️ Keyboard-First Editing

Work efficiently using keyboard shortcuts for finding and replacing text, copying formatting, and other common editing tasks.

Press `F1` to open the keyboard shortcut reference.

---

## 📥 Download & Installation

Download the Windows ZIP package from the **Releases** page of the GitHub repository.

### STEP 01. Extract the ZIP Archive

Download and extract the ZIP archive to a folder on your computer.

<p align="center">
  <img src="https://github.com/user-attachments/assets/8345dcef-ae43-4cf2-8c37-ebca27c15f8f" alt="Extracting the OpenHAN ZIP Archive" width="600">
</p>

### STEP 02. Open the Application Folder

Navigate to the extracted `win-unpacked` directory.

<p align="center">
  <img src="https://github.com/user-attachments/assets/c9cf906f-8436-48a4-91f6-8d5bee9faeaa" alt="OpenHAN Application Folder" width="680">
</p>

### STEP 03. Launch OpenHAN

Double-click `OpenHAN.exe` to launch the application.

<p align="center">
  <img src="https://github.com/user-attachments/assets/5acef755-ad7d-4b98-a0bf-947ff86fb3e2" alt="Launching OpenHAN" width="680">
</p>

> **Important:** Keep the executable, DLL files, and `resources` folder together. The ZIP distribution does not require a separate installer. Application settings are stored in your Windows user profile.

---

## 📖 Quick Start

### 1. 🆕 Create a New Document

Choose a built-in template or press `Alt+N` to create a blank document.

### 2. 📂 Open an Existing File

Press `Ctrl+O` to open HWP, HWPX, OHAN, TXT, or HTML documents.

### 3. ✍️ Edit Your Document

Use the formatting toolbar to style text, insert tables, and add images.

### 4. 🪄 Remove Image Backgrounds with AI

Select an image and press `Ctrl+Shift+K`.

Refine the background removal results and apply them to your document, or save the image as a transparent PNG.

<p align="center">
  <img src="https://github.com/user-attachments/assets/ba0257a6-8a48-4f24-98df-71ac05e10186" alt="OpenHAN AI Image Background Removal Workspace" width="680">
</p>

### 5. 💾 Save Your Document

Press `Ctrl+S` to save your document in HWP, HWPX, or OHAN format.

<p align="center">
  <img src="https://github.com/user-attachments/assets/2c353bab-ec23-4d5a-88be-7c5d10b587bc" alt="Saving a Document in OpenHAN" width="560">
</p>

### 6. 📤 Export & Print

Export your document as a PDF from the File menu, or press `Ctrl+P` to print.

<p align="center">
  <img src="https://github.com/user-attachments/assets/807cecc6-a92c-4e63-a45b-ea1d36a02cdb" alt="OpenHAN Document Editing and Printing" width="680">
</p>

### 7. 🎨 Customize Your Workspace

Navigate to **Tools → Preferences** to change the interface theme and other application settings.

---

## 📁 Supported File Formats

| Format | Open | Save / Export |
| :--- | :---: | :---: |
| HWP 5.0 (`.hwp`) | ✅ | ✅ |
| HWPX (`.hwpx`) | ✅ | ✅ |
| OpenHAN (`.ohan`) | ✅ | ✅ |
| Plain Text (`.txt`) | ✅ | ✅ Export |
| HTML (`.html`, `.htm`) | ✅ | ✅ Export |
| PDF (`.pdf`) | — | ✅ Export |

### Compatibility Notes

The following formats are not supported:

- HWP 3.0 and earlier
- Password-protected HWP documents
- Distribution-protected HWP documents

Some OpenHAN-specific formatting, such as bullet lists and block quotes, may be converted into standard paragraphs when saving to HWP or HWPX.

For the best preservation of OpenHAN-specific formatting, use the **native OHAN format**.

<p align="center">
  <img src="https://github.com/user-attachments/assets/98ac6bd4-d6b0-4bd9-8d46-65df27258262" alt="OpenHAN Document Compatibility" width="600">
</p>

---

## ⌨️ Keyboard Shortcuts

| Action | Shortcut |
| :--- | :--- |
| 🆕 New Document | `Alt+N` |
| 📂 Open File | `Ctrl+O` |
| 💾 Save | `Ctrl+S` |
| 🖨️ Print | `Ctrl+P` |
| 🔎 Find / Replace | `Ctrl+F` / `Ctrl+H` |
| ✍️ Character / Paragraph Formatting | `Alt+L` / `Alt+T` |
| 📐 Page Setup | `F7` |
| 🪄 AI Background Removal | `Ctrl+Shift+K` |
| 🖥️ Fullscreen | `F11` |
| ❓ Keyboard Shortcut Reference | `F1` |

---

## 🛠️ Technology Stack

OpenHAN is built using modern open-source technologies.

| Category | Technology |
| :--- | :--- |
| Desktop Application | Electron |
| User Interface | React |
| Document Editing Engine | Tiptap / ProseMirror |
| AI Background Removal | U²-Net |
| Local AI Inference | ONNX Runtime |
| File Processing | fflate / cfb |

Although OpenHAN makes use of international open-source technologies, **the OpenHAN application itself was conceived and developed entirely by Korean developers.**

---

## ✉️ Support & Bug Reports

If you encounter an issue, please report it through the repository's **GitHub Issues** page.

To help us investigate and resolve problems efficiently, include the following information:

- OpenHAN version
- Windows version
- Steps to reproduce the issue
- Expected behavior and actual results

For document compatibility issues, please attach a sample file with all personal or sensitive information removed.

---

## 📜 License & Credits

OpenHAN is distributed under the **MIT License**.

Bundled third-party components retain their respective licenses.

| Component | License |
| :--- | :--- |
| OpenHAN | MIT |
| U²-Net | Apache-2.0 |
| cfb | Apache-2.0 |
| ONNX Runtime | MIT |
| Tiptap / ProseMirror | MIT |
| fflate | MIT |

<p align="center">
  <img src="https://github.com/user-attachments/assets/edc61526-ba9d-4725-8f06-938f891363a9" alt="OpenHAN License and Credits" width="420">
</p>

---

<div align="center">

### 🇰🇷 PROUDLY MADE IN KOREA

**100% Korean-Developed**

### 📝 OpenHAN

**Your Words. Your Workspace.**

Familiar Writing. More Possibilities.

A New Document Editing Experience, Born in South Korea.

**Windows x64 · Version 2.0.0 · MIT License**

</div>
