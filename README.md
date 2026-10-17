# 📝 OpenHAN

### Familiar writing. More possibilities.

**A Korean word processor for Windows with HWP/HWPX support and built-in AI background removal.**

🪟 Windows x64 · 💎 v2.0.0 · 🎨 Three interface themes · 📜 MIT

[한국어 소개](README.ko.md)

OpenHAN brings document editing, tables, images, and page layout into one desktop workspace. Open an existing document, start with a template, and choose the interface that feels right for you.

## ✨ Key Features

- 📄 **HWP & HWPX Reading and Writing** — Open and save HWP 5.0 and HWPX documents, or use OpenHAN’s native `.ohan` format to retain its editor formatting.
- 🎨 **Three Interface Themes** — Choose the **2010**, **2018**, or **2024** theme. Switch to a dark interface while keeping the document page white.
- 🗂️ **Tabbed Documents** — Work with multiple documents, revisit recent files, and open additional windows.
- ✍️ **Detailed Text Formatting** — Adjust fonts, sizes, colors, character spacing, line spacing, paragraph alignment, and indentation. Use headings, lists, and format copying.
- 📊 **Table Editing** — Insert tables, add or remove rows and columns, and merge or split cells.
- 🖼️ **Images & AI Background Removal** — Remove backgrounds with the bundled U²-Net model running locally through ONNX Runtime. Refine the result with a magic wand, eraser, and restore brush, then insert it into your document or save a transparent PNG.
- 📐 **Page Layout Controls** — Set page dimensions, orientation, margins, page breaks, and page numbers. Use rulers and zoom controls to refine the view.
- 📤 **Export & Print** — Export documents as PDF, HTML, or plain text, and print through the desktop print dialog.
- 📋 **Built-in Templates** — Get started with templates such as a household budget, weekly planner, meeting minutes, and an award certificate.
- ⌨️ **Keyboard-Friendly Editing** — Find and replace text, copy formatting, and browse the searchable shortcut reference with **F1**.

## 📥 Download & Run

Download the Windows ZIP attached to this repository’s **Releases** page.

1. Extract the entire ZIP archive.
2. Open the extracted `win-unpacked` folder.
3. Launch **`OpenHAN.exe`**.

Keep the executable, DLLs, and `resources` folder together. No installer is required for this ZIP distribution; application settings are stored in your Windows user profile.

## 📖 Quick Start

1. 🆕 **Start a document:** Choose a template or press **Alt+N** for a blank document.
2. 📂 **Open a file:** Press **Ctrl+O** to open HWP, HWPX, OHAN, TXT, or HTML documents.
3. ✍️ **Edit and format:** Use the formatting tools to style text and add tables or images.
4. 🪄 **Remove an image background:** Select an image and press **Ctrl+Shift+K**. Run AI background removal, refine the edges, and apply the result.
5. 💾 **Save:** Press **Ctrl+S**, then choose HWP, HWPX, or OHAN as appropriate.
6. 📤 **Share:** Export to PDF from the file menu, or press **Ctrl+P** to print.
7. 🎨 **Customize:** Open **도구 → 환경 설정** to change the interface theme and other preferences.

## 📁 Document Formats

| Format | Open | Save / Export |
| --- | --- | --- |
| HWP 5.0 (`.hwp`) | ✅ | ✅ |
| HWPX (`.hwpx`) | ✅ | ✅ |
| OpenHAN (`.ohan`) | ✅ | ✅ |
| Plain text (`.txt`) | ✅ | ✅ Export |
| HTML (`.html`, `.htm`) | ✅ | ✅ Export as `.html` |
| PDF (`.pdf`) | — | ✅ Export |

HWP 3.0 and earlier, password-protected HWP files, and distribution-protected HWP files are not supported. Some OpenHAN formatting, including bullets and block quotes, is converted to ordinary paragraphs when saved as HWP/HWPX. Use **OHAN** when preserving OpenHAN-specific formatting matters. Layout fidelity can vary with document features and installed fonts.

## ⌨️ Handy Shortcuts

| Action | Shortcut |
| --- | --- |
| New document | `Alt+N` |
| Open | `Ctrl+O` |
| Save | `Ctrl+S` |
| Print | `Ctrl+P` |
| Find / Replace | `Ctrl+F` / `Ctrl+H` |
| Character / Paragraph formatting | `Alt+L` / `Alt+T` |
| Page setup | `F7` |
| Image background removal | `Ctrl+Shift+K` |
| Fullscreen | `F11` |
| Shortcut reference | `F1` |

## 🛠️ Built With

⚙️ **Electron & React** · ✍️ **Tiptap / ProseMirror** · 🧠 **U²-Net & ONNX Runtime** · 📦 **fflate & cfb**

## ✉️ Support

🐞 Report bugs through this repository’s **Issues** tab. Include your OpenHAN version, Windows version, steps to reproduce, and the expected result. For document compatibility issues, a small sample file without personal information is helpful.

💡 Feature requests and suggestions are welcome in Issues.

## 📜 License & Credits

OpenHAN’s package declares the **MIT License**. Bundled third-party components retain their respective licenses, including U²-Net and cfb (Apache-2.0), and ONNX Runtime, Tiptap / ProseMirror, and fflate (MIT).

OpenHAN is an independent project and is not affiliated with Hancom.

---

📝 *Your words. Your workspace. OpenHAN.*
