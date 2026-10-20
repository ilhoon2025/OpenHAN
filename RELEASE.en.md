# 📝 OpenHAN **v2.5.0** · *Official Release* · 🍎 macOS added

✨ **From HWP/HWPX editing to an AI assistant, Korean spell checking, official-style rewriting, and AI background removal — on PC and phone.**

### 📥 Downloads

| Platform | File | Notes |
| :--- | :--- | :--- |
| 🪟 **Windows installer** | [`OpenHAN-2.5.0-Setup.exe`](https://github.com/ilhoon2025/OpenHAN/releases/download/v2.5.0/OpenHAN-2.5.0-Setup.exe) | Creates Start menu and desktop shortcuts **(recommended)** |
| 🪟 **Windows portable** | [`OpenHAN-2.5.0-Portable.exe`](https://github.com/ilhoon2025/OpenHAN/releases/download/v2.5.0/OpenHAN-2.5.0-Portable.exe) | Single file, no installation |
| 🤖 **Android** | [`OpenHAN-2.5.0-Android.apk`](https://github.com/ilhoon2025/OpenHAN/releases/download/v2.5.0/OpenHAN-2.5.0-Android.apk) | Copy to your phone and install (allow unknown sources) |
| 🍎 **macOS (Apple silicon)** | [`OpenHAN-2.5.0-mac-arm64.dmg`](https://github.com/ilhoon2025/OpenHAN/releases/download/v2.5.0/OpenHAN-2.5.0-mac-arm64.dmg) | M1–M4 Macs |
| 🍎 **macOS (Intel)** | [`OpenHAN-2.5.0-mac-x64.dmg`](https://github.com/ilhoon2025/OpenHAN/releases/download/v2.5.0/OpenHAN-2.5.0-mac-x64.dmg) | Intel Macs · `.zip` also provided |

> ⚠️ The app is not code-signed, so **Windows SmartScreen** may warn on first launch — click **More info → Run anyway**.
>
> 🍎 The macOS app is not notarized, so the first launch shows an "unidentified developer" warning — **right-click the app → Open**, or run `xattr -cr /Applications/OpenHAN.app`.

### 🆕 What changed in v2.5.0

🍎 **macOS app** — builds for Apple silicon (arm64) and Intel (x64).

⌨️ **Android Korean input fixed** — Korean typed with a phone keyboard no longer disappears or doubles up.

🔑 **Built-in Pollinations key** — OpenHAN ships with its own Pollinations key, so AI works out of the box on the new endpoint with higher limits. You can still use your own key in **Tools → Settings → AI**.

### ✨ Added in v2.0

✨ **AI assistant** — say "write meeting minutes", "make a monthly budget table", or "switch to landscape" and it acts on the document. (`Ctrl+K, A`)

🔤 **Korean spelling & spacing infographic** — accuracy score, error-type bars, and fix cards; fix everything in one click. (`F8` check · `Ctrl+F8` auto fix)

🏛️ **Official / academic style rewriter** — turn casual text into Korean official-document style, academic style, report style, and more, compared side by side.

📱 **HWP summary & medium viewer** — skim a long HWP as phone-style cards: summary, key points, images, and tables, without opening it. (`Ctrl+K, P`)

🔑 **Free AI with automatic failover** — add free keys for Gemini · Groq · Mistral · Cerebras · OpenRouter and OpenHAN switches providers when a limit is hit. Works with no key via Pollinations; local AI (Ollama) is unlimited and offline.

🤖 **Android app** — phone-first layout, save via the share sheet, open HWP files from other apps.

🍎 **macOS support** — traffic-light buttons, ⌘ shortcuts, open from Finder.

💿 **Installer & default app** — Setup installer, and double-click hwp · hwpx · ohan · txt · html to open in OpenHAN.

🎨 **New per-theme logos** — one for each of 2010 · 2018 · 2024, plus the 2018 diagonal corner tab.

### 🛠️ Project Overview

🏷️ **Name:** OpenHAN  
💎 **Version:** 2.5.0  
🖥️ **Platforms:** Windows x64 · Android · macOS  
⚙️ **Core:** Electron · Capacitor · React · Tiptap / ProseMirror  
🧠 **AI:** OpenAI-compatible providers with failover · bundled U²-Net (ONNX Runtime, local)  
📜 **License:** MIT

### ✨ Core features

📄 **HWP & HWPX** read/write (HWP 5.0) — files saved by OpenHAN open in Hangul 2024 with fonts, colors, cell shading, merged tables, images, and page size intact.  
🎨 **Three themes** — 2010, 2018, 2024, plus a dark interface.  
🗂️ **Tabs and 12 templates**  
✍️ **Editing** — character/paragraph shape, tables, images, page numbers, page setup  
🪄 **Local AI background removal** with manual refinement and transparent PNG export  
⌨️ **Hangul-style shortcuts** — press **F1** to search them

### 📌 Notes

HWP 3.0 and earlier, password-protected, and distribution-protected HWP are not supported. Headers/footers, footnotes, shapes, and table captions are not handled yet; use **OHAN** to keep OpenHAN-specific formatting.

Text is sent to an AI provider only when you use an AI feature. API keys are stored in your OS account's encrypted storage. The keyless free provider is rate-limited, so adding a free Gemini or Groq key is recommended.

### ✉️ Support

Report bugs in **GitHub Issues** with the app version, platform, and steps to reproduce.

---

📝 *Your Words. Your Workspace. OpenHAN.*
