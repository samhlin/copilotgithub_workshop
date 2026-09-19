# 專案開發規則

## 技術限制

- 這是純前端專案，只用 HTML、CSS、原生 JavaScript。
- 禁止引入任何框架或套件，不要建立 `package.json`，不要執行 `npm install`。
- 不要引用外部 CDN，必須能離線運作。
- 檔案結構固定為根目錄的 `index.html`、`styles.css`、`app.js`。

## 程式風格

- 註解一律用繁體中文，變數與函式命名用英文 camelCase。
- CSS 顏色一律使用 `:root` 定義的 CSS 變數，不要寫死色碼。
- 使用 `const` / `let`，不要用 `var`。
- 產生 DOM 內容時用 `textContent` 或 `createElement`，不要用 `innerHTML` 組字串。

## 協作方式

- 動手改之前，先條列說明打算改哪些檔案、做什麼變動，等我確認後才開始。
- 一次只處理一件事，不要順手做我沒要求的重構。
- 改完後說明要怎麼在瀏覽器中驗證。
