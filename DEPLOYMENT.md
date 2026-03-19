# 🚀 GitHub Pages 部署指南

## 快速部署步驟

### 方法一：GitHub 網頁介面（推薦新手）

1. **創建 GitHub 帳號**（如果還沒有）
   - 前往 https://github.com
   - 點擊 "Sign up" 註冊

2. **創建新儲存庫**
   - 登入後，點擊右上角的 "+" → "New repository"
   - 儲存庫名稱：`dementia-maze-game`（或任何您喜歡的名稱）
   - 選擇 "Public"（公開）
   - ✅ 勾選 "Add a README file"
   - 點擊 "Create repository"

3. **上傳檔案**
   - 在儲存庫頁面，點擊 "Add file" → "Upload files"
   - 拖曳或選擇 `index.html` 檔案
   - 在下方填寫提交訊息：`Add dementia maze game`
   - 點擊 "Commit changes"

4. **啟用 GitHub Pages**
   - 點擊儲存庫上方的 "Settings"
   - 左側選單找到 "Pages"
   - Source 選擇：`Deploy from a branch`
   - Branch 選擇：`main`
   - Folder 保持：`/ (root)`
   - 點擊 "Save"

5. **等待部署完成**
   - 等待 1-3 分鐘
   - 重新整理頁面
   - 您會看到：✅ "Your site is live at https://yourusername.github.io/dementia-maze-game/"

6. **訪問您的遊戲**
   - 點擊上方顯示的網址
   - 遊戲就成功上線了！🎉

---

### 方法二：使用 Git 命令列（進階用戶）

```bash
# 1. 下載遊戲檔案到您的電腦
# 2. 在檔案所在資料夾開啟終端機

# 初始化 Git 儲存庫
git init

# 添加檔案
git add index.html README.md

# 提交
git commit -m "Add dementia maze game"

# 創建 main 分支
git branch -M main

# 連接到 GitHub（替換成您的儲存庫 URL）
git remote add origin https://github.com/yourusername/dementia-maze-game.git

# 推送到 GitHub
git push -u origin main
```

然後按照方法一的步驟 4-6 啟用 GitHub Pages。

---

## ✅ 部署檢查清單

- [ ] 已創建 GitHub 帳號
- [ ] 已創建新的儲存庫
- [ ] 已上傳 index.html 檔案
- [ ] 已在 Settings > Pages 啟用 GitHub Pages
- [ ] 已選擇 main 分支
- [ ] 等待 1-3 分鐘讓部署完成
- [ ] 成功訪問遊戲網址

---

## 🔧 常見問題

### Q: 為什麼我的網站顯示 404？
A: 請等待 1-3 分鐘，GitHub Pages 需要時間建置。如果超過 5 分鐘仍然 404，請檢查：
- 檔案名稱是否為 `index.html`（全小寫）
- 是否已在 Settings > Pages 正確設定

### Q: 我可以使用自訂網域嗎？
A: 可以！在 GitHub Pages 設定頁面有 "Custom domain" 選項。

### Q: 如何更新遊戲內容？
A: 
1. 修改 index.html 檔案
2. 在 GitHub 儲存庫中，點擊 index.html
3. 點擊編輯按鈕（鉛筆圖示）
4. 貼上新內容
5. 點擊 "Commit changes"
6. 等待 1-2 分鐘，變更就會生效

### Q: 這個遊戲是免費的嗎？
A: 是的！GitHub Pages 完全免費。

---

## 📱 分享您的遊戲

部署完成後，您可以：
- 複製網址分享給朋友、學生、或家人
- 在社群媒體分享
- 嵌入到其他網站中
- 用於教育或衛教活動

---

## 🎯 下一步

部署成功後，您可以：
1. 自訂遊戲內容
2. 修改視覺設計
3. 添加更多題目
4. 翻譯成其他語言

---

**需要協助？** 歡迎在 GitHub Issues 提問！

祝您部署順利！🚀
