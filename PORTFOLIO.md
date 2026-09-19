# 待辦清單 Web App

這是一個在 GitHub Copilot 實戰工作坊中完成的待辦清單 Web App。專案以簡潔的介面協助使用者新增、整理與追蹤日常待辦事項，也用來實際練習 Agent Mode、MCP 與 agentic workflow 的開發流程。

## 線上展示

[開啟線上展示](https://<你的帳號>.github.io/<你的repo名稱>/)

> 請將上方網址中的 `<你的帳號>` 與 `<你的repo名稱>` 替換成實際的 GitHub Pages 資訊。

## 功能

- 新增待辦事項，並限制文字長度為 120 個字元。
- 將待辦事項標記為已完成或取消完成。
- 逐筆刪除待辦事項。
- 依「全部」、「未完成」與「已完成」篩選清單。
- 顯示目前未完成的待辦事項數量。
- 清除所有已完成的待辦事項。
- 使用 `localStorage` 保留待辦事項資料。
- 依使用者的系統偏好初始化明亮或深色模式。
- 手動切換明亮與深色模式，並保存主題選擇。
- 在沒有符合篩選條件的項目時顯示提示文字。
- 提供鍵盤可操作的表單、按鈕與核取方塊，以及對應的無障礙標籤。

## 技術

- 使用純 HTML、CSS 與原生 JavaScript 建立。
- 不使用任何前端框架或第三方套件。
- 不引用外部 CDN，頁面可以離線運作。
- 使用 CSS 自訂變數集中管理色彩與介面樣式。
- 使用 `localStorage` 儲存待辦事項與主題設定。
- 使用 DOM API、`textContent` 與 `createElement` 建立動態內容。

## 開發方式

這個專案在 GitHub Copilot 實戰工作坊中完成，開發過程包含以下做法：

- 使用 GitHub Copilot Agent Mode，依需求建立並逐步調整待辦清單 Web App。
- 透過 MCP 連接 Microsoft Learn 與 GitHub，查詢官方文件及讀取 repository 的 issue。
- 使用 `.github/prompts` 中的 prompt 定義 issue 修復流程，讓 Agent 依序讀取 issue、提出修改計畫、等待確認、建立分支、驗證、提交、推送並建立 Pull Request。
- 使用 GitHub issue 與 Pull Request 追蹤功能需求和修正內容。

## 我學到什麼

- 如何把需求拆解成可驗證的前端功能，並在修改前先確認實作計畫。
- 如何使用原生 JavaScript 管理 DOM、事件、篩選狀態與瀏覽器儲存資料。
- 如何透過 `prefers-color-scheme` 與 CSS 變數設計明亮和深色主題。
- 如何使用 MCP 查詢官方文件與 GitHub issue，讓開發流程取得更可靠的上下文。
- 如何用 prompt 定義可重複的 issue 修復流程，並透過分支、commit 與 Pull Request 管理變更。
