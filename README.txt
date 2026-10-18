青魚手機 PWA

【安裝】PWA 必須放在 HTTPS 網站（或 localhost）才能安裝，直接雙擊 index.html 只能當一般網頁使用。
1. 把整個資料夾上傳到 GitHub Pages、Netlify、Cloudflare Pages 等靜態空間。
2. 用手機開啟網址。
   iPhone：Safari > 分享 > 加入主畫面
   Android：Chrome > 選單 > 安裝應用程式
3. 第一次開啟後即可離線使用。

【本機測試】在此資料夾執行：python3 -m http.server 8000，再開 http://localhost:8000

【更新版本】修改 index.html 後，把 sw.js 第一行的 qene-fish-v1 改成 v2，使用者才會拿到新版。

【檔案】index.html、manifest.webmanifest、sw.js、icons/、games/（青魚遊戲，內建，離線可玩，有自己的 sw.js，更新遊戲後請把 games/sw.js 的 VERSION 加一）
