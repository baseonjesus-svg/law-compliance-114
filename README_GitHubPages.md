# 05.管理處法務科-114年度法令遵循自行評估表（GitHub Pages 線上填寫版）

此專案可直接部署於 **GitHub Pages**，讓使用者線上填寫、匯出 CSV、列印 PDF。

---
## 📦 專案內容

| 檔案 | 說明 |
|------|------|
| index.html | 主頁面（可線上填寫） |
| README_GitHubPages.md | 本說明檔 |

---
## 🚀 部署教學（繁體中文）

### 步驟一：建立 Repository
1. 登入 [GitHub](https://github.com)
2. 點擊「New repository」
3. 名稱輸入：`law-compliance-114`
4. 選擇「Public」，不要勾選 Initialize README
5. 點擊「Create repository」

### 步驟二：上傳檔案
1. 下載此壓縮檔並解壓縮
2. 將裡面的檔案（`index.html`、`README_GitHubPages.md`）上傳到剛建立的 repo
   - 可直接拖曳進 GitHub 頁面的「Upload files」區塊

### 步驟三：啟用 GitHub Pages
1. 進入 Repository 頁面 → 點選 **Settings**
2. 左側選單中找到 **Pages**
3. 在「Source」下拉選擇 **Deploy from a branch**
4. 在「Branch」下拉選擇 **main / (root)** → 點「Save」
5. 約 30 秒後，GitHub 會顯示您的網站連結，例如：  
   👉 https://<您的帳號>.github.io/law-compliance-114/

### 步驟四：開啟線上填寫
使用者打開上述網址後，即可看到完整表單：
- 可直接在瀏覽器中輸入與勾選
- 點擊「匯出 CSV」可下載填寫結果
- 點擊「列印/另存為 PDF」可保存檔案
- 資料僅儲存在使用者端（localStorage），不會上傳伺服器

---
## 🔒 注意事項
- 本頁面為純前端靜態網頁，無伺服器端資料收集功能。
- 若要集中管理填寫結果，可搭配 Google Sheet 或第三方表單整合（可另行設定）。
- 若更新內容，直接上傳新版 index.html 覆蓋即可。

---
## 🧩 作者與版本
- 自動生成者：ChatGPT（OpenAI GPT-5 模型）
- 專案名稱：`law-compliance-114`
- 版本：v1.0（2025）
