# VibeCodingGeminiCLI
Vibe Coding Gemini CLI - Gemini CLI (Command Line Interface) 是 Google 推出的一款**開源 AI 代理**，它將強大的 Gemini 模型直接帶入您的**終端機 (Terminal)**，讓開發人員和其他使用者能夠透過**自然語言**來完成各種任務。

![gemini-screenshot](./images/gemini-screenshot.png)

**主要特色與功能：**

1.  **AI 程式碼助手 (Code Assistant)：**
    * 直接在終端機中進行程式碼**理解、生成、重構和除錯**。
    * 能夠處理多檔案編輯，並具有專案全域上下文的能力（透過 **Gemini 2.5 Pro** 模型和 **100 萬 Token** 上下文視窗）。
    * 可使用 `GEMINI.md` 檔案為特定專案定義專案規則和程式碼樣式，提供持久的專案上下文。

2.  **多功能終端機工具：**
    * **聊天與問答：** 進行技術問題諮詢、資料查找或錯誤排查。
    * **內建工具 (Built-in Tools)：**
        * **Google Search (網頁搜尋)：** 能夠即時獲取網路資訊來回答問題。
        * **檔案操作：** 讀取 (`read_file`) 和寫入 (`write_file`) 檔案。
        * **Shell 指令：** 執行終端機命令 (`run_shell_command`)。
        * **網頁擷取 (`web_fetch`)** 等。
    * **任務管理：** 可用於整理檔案/資料夾、處理資料庫等。

3.  **可擴展性 (Extensibility)：**
    * 支援 **Model Context Protocol (MCP)**：這是一個開放標準，允許開發人員透過執行伺服器來為 CLI 加入新的工具或功能，實現與外部工具的客製化整合。

4.  **運作模式：**
    * 採用 **ReAct (Reason and Act)** 迴圈，能夠進行多步驟推理，並決定使用哪些內建或外部工具來完成複雜任務（例如修復 Bug、建立新功能）。
    * 支援**互動模式**（聊天式對話）和**非互動模式**（直接提供提示用於指令碼或自動化）。

5.  **免費方案 (Free Tier)：**
    * 個人使用者只需登入 Google 帳號即可免費使用。
    * 通常提供高額度的免費使用量（例如：每分鐘最多 60 次請求，每天最多 1,000 次請求）。

6.  **整合：**
    * 與 **Gemini Code Assist** 服務緊密相關，其代理模式（例如 VS Code 擴充功能中的聊天功能）就是由 Gemini CLI 提供支援。

總結來說，Gemini CLI 是一款強大、開源且專為開發者設計的 AI 代理工具，它將 AI 協作能力直接帶入開發者最常使用的終端機環境。

---
*PS: 考量到您有 Python Flask 與 React 的開發經驗，Gemini CLI 在程式碼生成、除錯和專案上下文理解方面，對您的日常開發工作應該會很有幫助。*

# PROMPT
```bash
依據 https://github.com/google-gemini/gemini-cli 的內容的彙整製作一頁式的介紹說明網頁，並幫我填寫 project.md 與 AGENTS.md 的內容，網頁風格請參考 STYLE.md。
```

# 啟動
docs/index.html

# 參考
https://github.com/google-gemini/gemini-cli
