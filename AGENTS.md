# 本專案 Python 環境
- 一律使用本資料夾的 `.venv`，禁止全域 pip install。
- Windows 直譯器：`.\.venv\Scripts\python.exe`
- macOS/Linux：`.venv/bin/python`
- 只裝 requirements-core.txt 的標配 10 項；A 段選配套件要使用者明確點名才裝。
- 安裝或修環境後，一律跑 `verify_core.py`，看到 `CORE_OK: 10/10` 才算完成。

# 影音與語音工具（不在 .venv 裡）
- yt-dlp / ffmpeg / deno 是系統工具，用 winget / brew 裝，不要用 pip 裝進 .venv。
- yt-dlp 加 `--print` 時必須同時加 `--no-simulate`，否則不會真的下載。
- edge-tts 用 `uv tool install edge-tts` 裝在獨立環境；播放一律行內播放，禁止 Start-Process 開播放器視窗。
