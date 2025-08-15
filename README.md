# 💖 情人節開源浪漫頁（GitHub Pages 模板）

一鍵部署、免寫程式，只要改「設定」就能生成你的專屬浪漫頁。  
**功能**：點愛心放紙屑/煙火、在一起天數、音樂播放、相片牆拖放（3–9 張）＋自動輪播、網址參數分享、LocalStorage 暫存。

## 🚀 快速開始
1. 點右上角 **Use this template**（或按這個頁面的綠色 **Use this template** 按鈕）。
2. 取個新倉庫名稱，例如 `valentine-2025`。
3. 進入新倉庫 → **Settings → Pages → Build and deployment**  
   - Source: `Deploy from a branch`  
   - Branch: `main`、資料夾選 root（`/`）  
4. 開啟頁面 URL，就能看到你的網站。

> 這個專案是單檔 `index.html`，不需要 Node 或打包工具。

## 🛠️ 自訂
- 右上角 **設定**：修改名字、故事、主題色、紀念日；上傳 **MP3** 與 **照片**。
- 分享連結：按 **複製可分享連結**，設定會寫進網址參數（不包含 MP3/照片）。
- 也可以直接用網址參數：  
  `?lover=小花&sender=阿志&anniv=2024-05-20&story=我們第一次...&theme=%23ff4d6d`

## 🔒 授權 / 隱私
- 建議使用 MIT 授權（已預設）。  
- 音樂與照片保留在使用者瀏覽器端（LocalStorage），不會上傳。

## 🧩 想用 React / Vite？
本模板為單檔版。若要擴充為 React，可將邏輯拆為元件後以 Vite 部署 GitHub Pages。
