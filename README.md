# 【市場資訊筆記】2026年10月9日 網頁發佈專案

本專案為【市場資訊筆記】專供 GitHub 與 Vercel 一鍵快速部署的靜態響應式網頁專案包。

## 專案內容
- `index.html`：大字版自適應（Responsive）每日市場資訊筆記網頁，內置目錄跳轉、優雅深藍專業金融排版與移動端適配。
- `vercel.json`：Vercel 靜態路由重定向設定檔。
- `README.md`：部署操作手冊。

## 一鍵部署至 Vercel 指引

### 方法一：透過 GitHub 與 Vercel 網頁介面自動部署
1. 將本專案解壓後的檔案上傳或推送至 GitHub 的全新倉庫（Repository），例如 `market-notes-20261009`。
2. 登入 [Vercel 官方網站](https://vercel.com)。
3. 點擊 **"Add New..."** -> **"Project"**。
4. 導入剛剛建立的 GitHub 倉庫。
5. **Framework Preset** 保持為 `Other`，根目錄保持 `./`。
6. 點擊 **Deploy**，約 30 秒內即可獲得專屬公開瀏覽網址（例如 `https://market-notes-20261009.vercel.app`）。

### 方法二：透過 Vercel CLI 本地終端機快速部署
在解壓後的專案目錄下執行：
```bash
npm i -g vercel
vercel deploy --prod
```

---
©2026 迷途伴讀書僮。版權所有，請勿轉載。
