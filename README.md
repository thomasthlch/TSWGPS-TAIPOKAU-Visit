# 大埔滘自然護理區生態考察 — 出發前互動準備手冊

天水圍官立小學「奇妙科學研究所」大埔滘自然護理區生態考察的出發前互動準備手冊。

線上版：<https://thomasthlch.github.io/TSWGPS-TAIPOKAU-Visit/>

`index.html` 是完整單檔手冊（裝備清單、安全翻卡、十二月物種圖鑑、小測、可列印通行證、探險導航地圖）。地圖分頁可離線使用 GPS 地圖，也可切換 Google Maps，並可下載離線版手冊。推送到 `main` 後，GitHub Actions 會把這個靜態網站發佈到 GitHub Pages。

學校帳戶以 Google 登入（`@tswgps.edu.hk`，另含已授權的 `thomasthlch@gmail.com`）。登入後的小測答案寫入 Firebase 專案 `mrli-thlch` 的獨立路徑 `taipokau_handbook/taipokau_visit/students`。`lichihong@tswgps.edu.hk` 可在手冊內打開「成績統計」。規則片段在 `firebase/taipokau_handbook.rules.fragment`，必須併入現有完整規則，不能單獨部署。
