# 市場資訊筆記 - GitHub / Vercel 部署專案

本專案包含 2026 年 10 月 7 日《市場資訊筆記》之最新完整響應式網頁，字體已全面加大、排版極其清晰，支援手機、平板與電腦自適應閱讀。

## 專案內容
- `index.html`：2026 年 10 月 7 日最新《市場資訊筆記》大字版響應式網頁
- `vercel.json`：Vercel 部署設定檔
- `README.md`：部署說明文件

## 發佈至 GitHub 與 Vercel 指引

### 步驟一：推送到 GitHub
如果你已有本機 Git Repository，將檔案複製進去後執行：
```bash
git add .
git commit -m "Update Market Notes to 2026-10-07"
git push origin main
```
（如果是新建立的 Repo，在 GitHub 建立 `market-notes` 後，直接在網頁端點擊「Upload files」，拖放 `index.html`、`vercel.json` 與 `README.md` 即可提交）。

### 步驟二：Vercel 自動部署
只要 GitHub Repo 已與 Vercel 關聯，每次 `git push` 後 Vercel 會在 10 秒內自動拉取最新 `index.html` 完成即時上線！
