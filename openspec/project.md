# Project Context

## Purpose
- 建立 Gemini CLI 的一頁式中文介紹頁面，整合官方重點資訊並呈現 Futuristic 科技風格。
- 提供快速掌握產品亮點、安裝方式、進階能力與資源連結的靜態網站。

## Tech Stack
- 純前端靜態頁面：HTML5 + 原生 CSS。
- 以 Google Fonts (Orbitron、Inter) 提供科技感字體。

## Project Conventions

### Code Style
- 採用語意化 HTML 標籤，區分 `header`、`main`、`section`、`footer`。
- CSS 儘量集中於單一 `<style>` 區塊，使用 CSS 變數管理顏色與陰影。
- 避免引入非必要框架或 JavaScript。

### Architecture Patterns
- 單頁式資訊配置，使用 CSS Grid/Flexbox 排版。
- 內容模組依功能分段：核心亮點、安裝、發佈節奏、進階能力、認證、資源。

### Testing Strategy
- 主要透過手動檢視頁面於桌機與行動版的響應式表現。
- 使用瀏覽器開發者工具驗證連結與字體載入狀況。

### Git Workflow
- 以主分支為主的線性流程；提交前確保 HTML/CSS 通過自檢。
- Commit 訊息建議使用動詞開頭（如 `add`, `update`, `fix`）。

## Domain Context
- Gemini CLI 為 Google 推出的終端機 AI 代理工具，支援 MCP 擴充、搜尋定錨、Shell 操作等功能。
- 官方資料來源：<https://github.com/google-gemini/gemini-cli>。

## Important Constraints
- 遵循 STYLE.md 指定的 Futuristic 風格（深色背景、霓虹亮點、科技感字體）。
- 文件以繁體中文撰寫，保留關鍵術語的英文原文。
- 不新增後端服務或編譯流程。

## External Dependencies
- Google Fonts（fonts.googleapis.com / fonts.gstatic.com）。
- 官方參考連結：GitHub 倉庫、NPM、文件頁面與 GitHub Action。
