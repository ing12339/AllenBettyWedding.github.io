<<<<<<< HEAD
# AllenBettyWedding.github.io
=======
# Wedding Invitation Site (純前端)

這是一個極簡、漂亮、好維護的婚禮喜帖網站樣板。

## 你可以做什麼
- 一頁式介紹：主視覺、故事、婚禮資訊、RSVP、地圖與 FAQ
- 倒數計時、加入行事曆（.ics 檔）
- Netlify 表單（免寫後端）、或改用 Google 表單/其他服務
- 手機友善、好分享（Open Graph 標籤）

## 快速開始
1. 下載整包檔案，解壓縮。
2. 用 VS Code 開啟資料夾；把 `index.html` 裡的文字、日期、地址與圖片路徑換成你的資料：
   - 標題、雙方名字：`<title>`、`<h1>`。
   - 日期時間：把底部 `EVENT_ISO` 改成你的 ISO 時間（+08:00）。
   - 會場地址：`婚禮資訊` 與地圖 iframe 的 `q` 參數。
   - 圖片：把 `assets/img/cover.jpg`, `photo1.jpg`, `photo2.jpg`, `favicon.png` 換成你的圖。
3. RSVP 表單：
   - 如果部署在 **Netlify**：什麼都不用改，Netlify 會自動收表單。
   - 其他平台：把 `<form>` 的 `method`/`action` 換成 `https://formsubmit.co/你的Email`，或刪掉 `<form>` 改放「前往 Google 表單」連結。
4. 行事曆：開啟 `assets/invite.ics`，把標題、地點與時間換成你自己的。
5. 本地預覽：用任何靜態伺服器（例如 VS Code 的 Live Server）打開 `index.html` 看效果。

## 部署方式
- **GitHub Pages**（免費）
  1. 新增 repo，整包檔案推上去。
  2. 在 repo 設定 → Pages → Branch 選 main（或 gh-pages）；路徑選根目錄。
  3. 等幾分鐘就會有網址。
- **Netlify**（免費）
  1. 直接把資料夾拖到 Netlify 網站上。
  2. 網址會自動生成；若使用 Netlify Forms，RSVP 會直接收信。
- **Vercel**、**Cloudflare Pages** 也都可以。

## 自訂與延伸
- 自訂網址：綁定自己的網域，列印在實體喜帖上，或做 QR Code。
- 多語系：把 `lang="zh-Hant"` 換成 `lang="en"` 再另存一份 `index-en.html`。
- 相簿：新增 `Gallery` 區塊，直接放照片或連到 Google Photos。
- 音樂：加一個 `<audio controls>`，手機上預設靜音需手動播放。
- 隱私：加上隱私聲明頁，或在表單下方補充使用目的。

## 無障礙 & 最佳實務
- 所有圖片都有 `alt` 說明文字。
- 表單欄位有 `label`。
- 色彩對比與按鈕觸控尺寸友善。

祝你們婚禮籌備順利！🎉
>>>>>>> d789ed3 (first commit)
