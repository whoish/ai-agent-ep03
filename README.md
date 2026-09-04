# AI Agent 基本功 EP03 ｜ Agent 的「手腳」：它在你電腦上到底能做什麼

> 三師爸 Sense Bar ・ [youtube.com/@sensebar](https://www.youtube.com/@sensebar)

這是 **AI Agent 基本功 EP03** 的完整隨附資料。看完影片想自己動手的老師，這裡有你需要的一切。

## 🔗 線上看簡報

👉 **[點我線上觀看簡報](https://mathruffian-dot.github.io/ai-agent-ep03/slides.html)**（GitHub Pages，手機也能看）

## 📦 這個 repo 有什麼

| 檔案 | 說明 |
|------|------|
| [`slides.html`](slides.html) | EP03 完整簡報（可離線開啟，← → 切頁、F 全螢幕） |
| [`EP03_大綱.md`](EP03_大綱.md) | 本集大綱與每段現場 demo 腳本 |
| [`EP03_教學檔案處理_工具列表.md`](EP03_教學檔案處理_工具列表.md) | 老師的 Python 工具清單（痛點／套件／一句話） |
| [`EP03_教學檔案處理_工具列表.pdf`](EP03_教學檔案處理_工具列表.pdf) | 上面清單的一頁式 PDF，方便列印／下載 |
| [`AGENT_SETUP_教學檔案處理工具包.md`](AGENT_SETUP_教學檔案處理工具包.md) | **給 AI Agent 讀的安全安裝指南** |
| [`install_windows.ps1`](install_windows.ps1) | Windows 核心工具自動安裝與驗證腳本 |
| [`requirements-core.txt`](requirements-core.txt) | 已篩選的核心 Python 套件清單 |
| [`EP03_Python範例.md`](EP03_Python範例.md) | 完整工具地圖與選用說明 |
| [`make_pdf.py`](make_pdf.py) | 重新產生 PDF 的腳本 |

## 🚀 一鍵安裝核心工具（重點！）

把 [`AGENT_SETUP_教學檔案處理工具包.md`](AGENT_SETUP_教學檔案處理工具包.md) 交給你的 AI Agent
（Claude Code / Codex / Antigravity / OpenCode 都可以），然後說：

> 「讀這份檔案，只安裝裡面的核心工具，選用工具先不要裝。」

你的 Agent 會執行同一支 PowerShell 腳本，以 Python 3.12 建立本 repo 專用的 `.venv`、
安裝 10 項核心工具並驗證。OCR、影音、Office COM 等進階工具不會自動安裝，
避免初學者卡在系統相依或讓 Agent 反覆排錯、浪費 Token。

也可以在 Windows PowerShell 直接執行：

```powershell
powershell.exe -NoProfile -ExecutionPolicy Bypass -File ".\install_windows.ps1"
```

> Claude Code、Codex App、Antigravity、OpenCode 在 Windows 原生模式都可使用。
> 若 OpenCode 跑在 WSL，需在 WSL 另建 Linux Python 環境，不能共用 Windows `.venv`。

## 🧰 工具清單速覽

涵蓋老師天天在處理的 **Word／Excel／PPT／PDF**：套印獎狀、出考卷、成績分析、
教材轉簡報、PDF 合併與浮水印、掃描講義 OCR…等。完整內容見上方清單檔。

## 📺 相關集數

- EP01：用 Agent 來學習 Agent
- EP02：使用 Agent 前，你一定要知道的基本觀念
- **EP03：Agent 的手腳（本集）**
- [EP04：連接外部工具（MCP）](https://github.com/mathruffian-dot/ai-agent-ep04)
- EP05（預告）：技能（Skill）

---

> 歡迎自由下載、分享、改作。製作：三師爸 Sense Bar
