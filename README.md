# AI-900 Mock Exam Website

這是 AI-900 互動模擬考網站，可部署到 GitHub Pages。

## 功能

- 45 題、60 分鐘模擬考預設值
- 右上角倒數計時
- 單選、多選、是/否、下拉填空、配對、拖放排序互動
- 交卷後顯示 Microsoft Certification Score Report 風格成績頁
- 分數下方只顯示答錯題目的答案與解析
- 重考一次按鈕

## GitHub Pages 自動部署

此專案已包含 `.github/workflows/deploy-pages.yml`。

推送到 `main` 分支後，GitHub Actions 會自動部署網站到 GitHub Pages。

第一次使用時，請到 GitHub repo：

1. Settings
2. Pages
3. Build and deployment
4. Source 選擇 `GitHub Actions`

之後每次更新 `index.html` 並 push 到 `main`，網站會自動更新。

## 本機預覽

可直接開啟 `index.html`，或使用任意靜態網站伺服器預覽。
