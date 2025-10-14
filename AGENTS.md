<!-- OPENSPEC:START -->
# OpenSpec Instructions

These instructions are for AI assistants working in this project.

Always open `@/openspec/AGENTS.md` when the request:
- Mentions planning or proposals (words like proposal, spec, change, plan)
- Introduces new capabilities, breaking changes, architecture shifts, or big performance/security work
- Sounds ambiguous and you need the authoritative spec before coding

Use `@/openspec/AGENTS.md` to learn:
- How to create and apply change proposals
- Spec format and conventions
- Project structure and guidelines

Keep this managed block so 'openspec update' can refresh the instructions.

<!-- OPENSPEC:END -->

## 工作概覽
- 專案聚焦於 Gemini CLI 的單頁式介紹網站與相關說明文件。
- 須遵守 Futuristic 科技風格：深色背景、霓虹藍紫重點、幾何格線布局、科技感字體（Orbitron/Inter）。
- 內容以繁體中文撰寫，保留產品名稱、指令、專有名詞的英文。

## 實作指引
- 新增或調整頁面時優先編輯 `docs/index.html`，採語意化結構並保持無 JS 依賴。
- 風格調整集中於同一 `<style>` 區塊，使用 CSS 變數維持一致色彩。
- 若需新增資源，請確認來源可信且與 Gemini CLI 官方資訊一致。

## 文件維護
- `openspec/project.md` 保存整體背景與技術約束，更新內容時同步檢查該文件。
- 本 `AGENTS.md` 記錄協作流程與風格原則，如有重大流程改動需先告知使用者。
- 其他專案說明文件（如 README）如需修改，請維持與官方資料一致並提供引用來源。

## 驗證建議
- 修改後使用瀏覽器或靜態伺服器檢視頁面排版、字體載入、連結是否正常。
- 檢查 HTML 是否通過基本語法驗證（例如 VS Code / IDE 的 HTML 提示）。
- 若新增連結，確認 HTTP 狀態為 200 且不需額外授權才能存取。
