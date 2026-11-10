# Probably Stolen 模組

《Probably Stolen》的遊戲模組，使用遊戲官方的模組格式（不需要 BepInEx / MelonLoader）。

> [!IMPORTANT]
> - **本模組是第三方製作，與遊戲官方無關，請自行評估後使用。**
> - **本模組使用 AI 設計，不喜勿用。**

## 模組清單

### Frequency Radio（黑洞頻率電台）

<img src="images/frequency_radio/preview.png" alt="Frequency Radio（黑洞頻率電台）" width="450">

極光造成的時空交錯，讓你所在的現實世界的廣播訊號，接進了你的店。

卡帶播放器多一個「電台」分頁：卡帶／電台切換，選國家/地區、選電台，收聽真實的網路廣播。卡帶和電台同時只會播一個。

- 收錄 70 個國家/地區、35,677 台：音樂台、新聞台，以及動漫 / J-pop / K-pop / Vocaloid 網路電台，有類型標示（Pop、JPop、KPop、Anime、News…）。
- 選台：先選國家/地區，台數多的再選州／省（加州、巴伐利亞、浙江…，中文介面顯示中文地名），再選電台；離你最近的國家/地區排在前面。
- 搜尋：輸入台名、類型或國家/地區，所有國家/地區的電台一起找，點一下就播。
- 有些電台只開放在官網收聽：選台後模組會在背景打開官網並幫你按下播放（標示「經官網播放」）；自動播放不成功時會打開官網畫面，讓你自己按播放。
- 電台放不出來時會跳出「無法播放」提示；只開放當地網路收聽的台也會一併說明。
- 電台分頁時，控制鈕作用在電台：播放、停止、上一台／下一台；按「隨機」隨機挑一台播。
- 每一台各自記住自己的音量和載入緩衝時間（電台卡頓時可延長載入緩衝）；自動音量平衡（預設開啟）會把小聲和大聲的台調到差不多。勾「統一音量」「統一緩衝」就所有電台用同一個設定，各台原本的設定會保留。
- 按星星把電台加到最愛，在「最愛」分頁直接點選播放。
- 韓文、希臘文、泰文等遊戲字型沒有的台名，用 Windows 內建字型顯示。
- 播放時卡帶播放器會飄出音符。
- 自動平衡、統一音量、統一緩衝、播放飄音可以直接在卡帶播放器上切換，也可以在模組設定調整。

**下載**：[Steam 工作坊](https://steamcommunity.com/sharedfiles/filedetails/?id=3830589099)　｜　[更新紀錄](CHANGELOG.md#frequency-radio黑洞頻率電台)

啟用時遊戲會顯示權限警告：網路（收聽電台）、Steam（經官網播放的電台使用 Steam 內建的瀏覽器）。

<details open>
<summary>內容預覽</summary>

<img src="images/frequency_radio/01.png" alt="預覽 1：卡帶播放器的電台分頁" width="450">
<img src="images/frequency_radio/02.png" alt="預覽 2：選電台" width="450">
<img src="images/frequency_radio/03.png" alt="預覽 3：選國家/地區：離你近的排前面" width="450">
<img src="images/frequency_radio/04.png" alt="預覽 4：選國家/地區（第 2 頁）" width="450">
<img src="images/frequency_radio/05.png" alt="預覽 5：經官網播放的電台" width="450">
<img src="images/frequency_radio/06.png" alt="預覽 6：經官網播放的電台（第 2 頁）" width="450">

</details>

### Frequency TV（黑洞頻率電視）

<img src="images/frequency_tv/preview.png" alt="Frequency TV（黑洞頻率電視）" width="450">

極光造成的時空交錯，讓你所在的現實世界的影像訊號，接進了你的店。

- 打開「查看日曆」，日曆／夜間報告／狀態旁邊多一個「電視」分頁：在遊戲裡直接看影片網站，原畫質播放。
- 右上角的網站選單可以切換 18 個影片網站：YouTube、bilibili、ニコニコ、Twitch、Dailymotion、Vimeo、VK Видео、RUTUBE、OK Видео、CDA、ARD Mediathek、ZDF、RTVE Play、TVer、ABEMA、優酷、愛奇藝、動畫瘋（部分網站只開放當地網路收看，或要登入才能看高畫質）。
- 網站選單依你所在的國家/地區排序，當地常用的網站排在前面；第一次打開的預設網站也依所在地決定，之後會記住你上次選的網站。
- 「電視」旁邊多一個「短影片」分頁：用手機大小的直式畫面看短影片，可切換 YT Shorts、IG Reels、FB Reels、TikTok、Snapchat、抖音、快手、小紅書、NAVER 클립、Moj、VK Клипы、RUTUBE Shorts、Kwai（部分網站要登入，或只開放當地網路收看）。用滑鼠按住往上下左右拖曳就是滑動，也可以用滾輪。
- 網站沒有回應時，畫面上會顯示說明；只開放當地網路收看的網站也會一併說明。
- 用滑鼠點選、捲動；滑鼠移到畫面上就能打字搜尋（支援中文輸入法）；支援 Ctrl+C／X／V／A（複製、剪下、貼上、全選）。
- 在畫面上按右鍵：上一頁、重新整理、複製網址；短影片分頁還可以切換橫式／直式。
- 分頁旁的小按鈕：上一頁、首頁（目前的網站）、暫停。
- 電視分頁的視窗可以拖曳移動，用右下角拉把或大小按鈕（100 / 75 / 50 / 35%，右鍵恢復原狀）調整大小，位置和大小會記住；其他分頁維持遊戲原本的位置和大小。
- 在電視分頁關掉日曆，影片繼續播，牆上的日曆螢幕變成小電視；點螢幕回到電視分頁。
- 牆上螢幕的掃描線效果可以開關（分頁旁的「掃描線」或模組設定）。
- 影片音量用網站播放器的音量調整。

**下載**：[Steam 工作坊](https://steamcommunity.com/sharedfiles/filedetails/?id=3836903387)　｜　[更新紀錄](CHANGELOG.md#frequency-tv黑洞頻率電視)

啟用時遊戲會顯示權限警告：Steam（使用 Steam 內建的瀏覽器播放）。

<details open>
<summary>內容預覽</summary>

<img src="images/frequency_tv/01.jpg" alt="預覽 1：日曆裡的電視分頁" width="450">
<img src="images/frequency_tv/02.jpg" alt="預覽 2：在遊戲裡播放影片" width="450">
<img src="images/frequency_tv/03.jpg" alt="預覽 3：關掉日曆後，牆上的螢幕繼續播" width="450">
<img src="images/frequency_tv/04.jpg" alt="預覽 4：牆上螢幕的掃描線效果" width="450">
<img src="images/frequency_tv/05.jpg" alt="預覽 5：電視分頁的網站選單" width="450">
<img src="images/frequency_tv/06.jpg" alt="預覽 6：bilibili" width="450">
<img src="images/frequency_tv/07.jpg" alt="預覽 7：Twitch 直播" width="450">
<img src="images/frequency_tv/08.jpg" alt="預覽 8：動畫瘋" width="450">
<img src="images/frequency_tv/09.jpg" alt="預覽 9：VK Видео" width="450">

</details>

## 安裝

在模組的 Steam 工作坊頁面按「訂閱」→ 開遊戲 → 主選單「Mods」啟用 → 重開遊戲。

---

## 支持作者

喜歡這個模組的話，想支持作者，可以考慮加入 **[遊戲聯合公國 Discord](https://discord.gg/nTE6CBb)** 幫我們擴展人數。
這是一個廣納各種遊戲的交流社區，不侷限單一遊戲，族群偏向上班族較多，不想要加入的話也不勉強。

<a href="https://discord.gg/nTE6CBb"><img src="https://img.shields.io/badge/Discord-%E5%8A%A0%E5%85%A5%E9%81%8A%E6%88%B2%E8%81%AF%E5%90%88%E5%85%AC%E5%9C%8B-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="加入遊戲聯合公國 Discord" height="40"></a>

<a href="https://discord.gg/nTE6CBb"><img src="images/gdg_logo.png" alt="遊戲聯合公國 Grand Duchy of Games" width="420"></a>

也可以透過 Ko-fi 贊助作者，你的支持是持續更新的動力：

<a href="https://ko-fi.com/xvideos8kuhd"><img src="images/kofi_button.png" alt="Support me on Ko-fi" width="320"></a>
