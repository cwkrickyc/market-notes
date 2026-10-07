# 市場資訊筆記 - Vercel 部署專案

本專案包含 2026 年 10 月 6 日《市場資訊筆記》之完整響應式靜態網頁。

## 部署至 Vercel 方法

### 方法 A：透過 GitHub 連結部署（最推薦，日後自動更新）
1. 在 GitHub 上建立一個新的公開或私有 Repository（例如：`market-notes`）。
2. 將本專案解壓後的檔案（`index.html` 與 `vercel.json`）上傳至該 GitHub Repo。
3. 登入 [Vercel](https://vercel.com)。
4. 點擊 **「Add New...」** ➡️ **「Project」**。
5. 選擇剛才建立的 GitHub Repo，直接點擊 **「Deploy」**。
6. 約 15 秒後即可獲得專屬網址（例如：`https://market-notes.vercel.app`）。

### 方法 B：使用 Vercel CLI 本地一鍵部署（終端機指令）
1. 在電腦終端機安裝 Vercel CLI：
   ```bash
   npm i -g vercel
   ```
2. 進入本專案資料夾並執行：
   ```bash
   vercel
   ```
3. 按照終端機提示按 Enter 確認，即時完成部署！
