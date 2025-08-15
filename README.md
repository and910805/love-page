# 💖 情人節開源浪漫頁（GitHub Pages 模板）

一鍵部署、免寫程式，只要改「設定」就能生成你的專屬浪漫頁。  
**功能**：點愛心放紙屑/煙火、在一起天數、音樂播放、相片牆拖放（3–9 張）＋自動輪播、網址參數分享、LocalStorage 暫存。

好，我幫你改 README 的說明，把 **GitHub Pages 部署** 部分寫清楚（不需要 Jekyll Actions），再加上 **直接在電腦桌面打開的版本** 說明。

你可以把這段直接複製到 README.md ：

---

## 🚀 快速開始（GitHub 直接部署）

1. 點右上角 **Use this template**（或按頁面上的綠色 **Use this template** 按鈕）。
2. 取個新倉庫名稱，例如：`valentine-2025`。
3. 進入新倉庫 → **Settings → Pages → Build and deployment**

   * **Source**：`Deploy from a branch`
   * **Branch**：`main`（或 `mainer`，依你的分支名稱）
   * **Folder**：選 `/ (root)`
4. 進入新倉庫 → Actions
   - 搜尋並選擇 Jekyll using Docker image 工作流
   - 按 Configure → 直接 Commit 到分支，啟用工作流
4. 等候 1～3 分鐘，回到 **Settings → Pages** 頁面最上方會看到：

   ```
   Your site is live at https://你的帳號.github.io/你的-repo-名稱/
   ```
5. 點擊網址，就能看到你的浪漫網站 🎉

> ⚠ **注意**：這個專案是純 HTML，不需要選 Jekyll 或其他 Actions 部署，GitHub Pages 會自動幫你處理。

---

##  放在電腦桌面直接打開版本

如果你不想用 GitHub Pages，也可以直接在本機打開網站：

1. 在這個 repo 頁面點擊 **Code → Download ZIP** 下載專案壓縮檔。
2. 解壓縮到電腦任意資料夾（例如桌面）。
3. 直接雙擊 `index.html`，用瀏覽器打開，就能看到網站。

> **小提醒**：本機打開版本一樣能用所有功能，但網址分享功能只會在本機作用，因為沒有線上部署。

##  自訂
- 右上角 **設定**：修改名字、故事、主題色、紀念日；上傳 **MP3** 與 **照片**。
- 分享連結：按 **複製可分享連結**，設定會寫進網址參數（不包含 MP3/照片）。
- 也可以直接用網址參數：  
  `?lover=小花&sender=阿志&anniv=2024-05-20&story=我們第一次...&theme=%23ff4d6d`

##  授權 / 隱私
- 建議使用 MIT 授權（已預設）。  
- 音樂與照片保留在使用者瀏覽器端（LocalStorage），不會上傳。

##  想用 React / Vite？
本模板為單檔版。若要擴充為 React，可將邏輯拆為元件後以 Vite 部署 GitHub Pages。
我找時間在出一版React版本
