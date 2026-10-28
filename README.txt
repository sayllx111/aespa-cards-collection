小卡管理簿｜iPhone 主畫面網頁 App

重要：這個資料夾是可部署的 PWA 網頁 App 套件。要讓 iPhone 能「加入主畫面」並以 App 形式開啟，需要先放到支援 HTTPS 的網站主機上；直接從「檔案」開啟 HTML 不會變成真正的 PWA。

快速使用（GitHub Pages 免費部署）：
1. 在 GitHub 建立一個新的 repository。
2. 將此資料夾內的所有檔案（index.html、manifest.json、sw.js、icon-192.png、icon-512.png）上傳到 repository 根目錄。
3. 到 repository 的 Settings → Pages。
4. 在 Build and deployment 選 Deploy from a branch；選 main 分支與 /(root)，按 Save。
5. 等待網站發布完成，打開 GitHub Pages 顯示的 HTTPS 網址。
6. 在 iPhone 的 Safari 開啟該網址 → 點分享按鈕 →「加入主畫面」→ 開啟「以網頁 App 方式打開」（若有顯示）→ 加入。

資料儲存：
- 小卡資料保存在這台 iPhone 的 Safari 網站資料中。
- 不會自動同步其他裝置；請在 App 內定期匯出 JSON 備份。
- 若清除 Safari 網站資料，可能會刪除資料。
- 若要跨裝置同步或雲端備份，需要另外加入帳號／資料庫功能。

若下載連結在 ChatGPT App 內點了會跳掉：
- 先長按下載連結，選「開啟連結」或「在 Safari 中開啟」（若選單有此選項）。
- 也可點連結後用分享按鈕選「儲存到檔案」。
- 這份 ZIP 套件把多個檔案打包在一起，比單獨下載 HTML 更適合部署。
