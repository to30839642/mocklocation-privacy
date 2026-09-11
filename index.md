---
layout: default
title: Privacy Policy — Mock Location
---

<a id="en"></a>

# Privacy Policy

[English](#en) · [中文](#zh)

This policy covers the Android application **Mock Location** (模擬定位), package name
`com.twenty.mocklocation`, developed and published on Google Play by **to**.

- **Effective date:** 2026-10-01
- **Developer:** to
- **Contact:** to30839642@gmail.com

---

## In one line

This app does not collect, upload or sell your location. The favourites and routes you create stay on your device.

---

## 1. What this app does not do

- **It does not collect your location.** Your real position is read once, only when you press “Device location”, to move the map to where you are. It is used and discarded — never stored, never sent anywhere.
- **There is no account.** No registration, no email address, no phone number, no identity of any kind.
- **There are no analytics.** The app contains no behavioural analytics, usage statistics or crash reporting SDK.
- **Nothing is sold.**

## 2. Where your data lives

Everything you create — favourites, routes, tags, app settings — is stored on your device in a Room database and DataStore. The developer cannot read it.

If you have Android’s automatic backup switched on, that data is backed up to your own Google account by the platform. The map tile cache is explicitly excluded from those backups and from device-to-device transfer.

You can export your favourites, tags, routes and settings to a single JSON file at any time under **Settings → About and backup**, and routes to a GPX file. On import the app reads the file you picked yourself; its contents go into the local database and are never uploaded. Uninstalling the app deletes all local data.

## 3. Connections that leave the device

The app makes four kinds of outbound connection. All of them serve a feature, and none of them carries your identity:

| Destination | What is sent | Why |
|---|---|---|
| `tiles.openfreemap.org` | The coordinates of the map area on screen | To download map tiles |
| The device’s address lookup service | The text you search for, or a coordinate you select | Address search and reverse lookup. Supplied by the device vendor; on most devices this is Google |
| The host of a shortened map link you paste | The short link itself | To expand it into coordinates |
| Google AdMob | See below | To show ads |

**On IP addresses:** every one of those connections lets the other end see your IP address. That is how the network works rather than something this app adds, but it does leave your device, so it is listed here.

**On expanding short links:** the app follows the link’s redirect chain, up to six hops, so the host it finally reaches may not be the one you pasted. The request carries a fixed User-Agent string that identifies nothing about you.

## 4. Advertising

The app uses Google AdMob. To serve and measure ads, AdMob collects your **advertising ID and device/usage information**, and shares it with Google and its advertising partners. The developer receives only aggregated performance reports, never individual records.

- How Google uses this data: <https://policies.google.com/technologies/partner-sites>
- You can reset or delete your advertising ID, or switch off ad personalisation, under **Settings → Privacy → Ads** on Android.
- The app offers “Remove ads”: watch one rewarded ad and no ads appear for the next 24 hours. Watching more adds to that, up to a maximum of 7 days.

**Your location data is never passed to the advertising service.**

## 5. Permissions

| Permission | Used for |
|---|---|
| `ACCESS_FINE_LOCATION` / `ACCESS_COARSE_LOCATION` | Reading your real position once, when you press “Device location” |
| `ACCESS_MOCK_LOCATION` | Android requires this declaration for the app to appear in the developer-options list of mock location apps. It is an eligibility declaration, not a runtime permission |
| `INTERNET` / `ACCESS_NETWORK_STATE` | Map tiles, address lookup, expanding short links, ads |
| `FOREGROUND_SERVICE` / `FOREGROUND_SERVICE_SPECIAL_USE` | Supplying test coordinates from a foreground service after you start a simulation |
| `POST_NOTIFICATIONS` | The status notification with its pause and stop controls |
| `WAKE_LOCK` | Only while you have chosen continuous screen-off playback |
| `com.google.android.gms.permission.AD_ID` | Reading the advertising ID, for serving and measuring ads |
| `ACCESS_ADSERVICES_AD_ID` / `ACCESS_ADSERVICES_ATTRIBUTION` / `ACCESS_ADSERVICES_TOPICS` | The Android Privacy Sandbox advertising APIs |

The last two rows are added by the Google ad SDK rather than declared by the app itself.

## 6. Data security

Your data never leaves your device, so there is no server or database on the developer’s side holding it — there is nothing to leak because nothing is taken. On the device, that data is protected by Android’s application sandbox and cannot be read by other apps.

Of the connections the app makes itself, map tiles and ads use HTTPS; expanding a short link follows the scheme of the URL you pasted and its redirects. Address lookup is performed on the app’s behalf by the Android system, and how it travels is decided by the system and the device vendor.

## 7. Data retention

The developer keeps no data, so there is no retention period to state.

What you create stays on your device until you delete it or uninstall the app. If Android’s automatic backup is switched on, how long that backup is kept is governed by Google’s policy and is outside the developer’s control.

## 8. International transfers

The map tile servers (OpenFreeMap) and Google AdMob’s servers are located outside Taiwan, so the connections listed in section 3 cross borders. They carry nothing that identifies you, but as noted there, the other end sees your IP address.

## 9. About the feature itself

This app supplies test coordinates through Android’s official developer-options mechanism. **It does not bypass an application’s detection of mock locations.** Whether to accept a mock coordinate is each application’s own decision, and it is up to you to make sure your use complies with the terms of the services you use.

## 10. Children

This app is not directed at children under 13 and does not knowingly collect their personal data.

## 11. EU users (GDPR)

On first launch the app asks about advertising consent through Google’s User Messaging Platform; where the law requires consent (the EU/EEA and the UK) the consent form is shown. You may decline; ads still appear, but are not personalised. **No request reaches an ad server before that consent flow has finished.**

Because the app collects no personally identifying data and has no accounts, there is no personal data held by the developer for you to access, correct or erase. Exercise advertising-related rights through the Google link in section 4.

## 12. US users (CCPA/CPRA)

The developer does not sell your personal information and receives nothing that identifies you.

The app uses Google AdMob to serve ads. Under CPRA, providing an advertising ID for cross-context behavioural advertising may amount to “sharing”. You can stop that use by switching off ad personalisation, or resetting or deleting your advertising ID, under **Settings → Privacy → Ads** on Android; advertising-related rights can also be exercised through the Google link in section 4.

## 13. Changes

Any change to this policy updates the effective date on this page. Significant changes are also noted in the app’s release notes.

## 14. Contact

**to30839642@gmail.com**

---

<a id="zh"></a>

# 隱私權政策

[English](#en) · [中文](#zh)

本政策適用於 Android 應用程式 **模擬定位**（英文名稱 Mock Location，套件名 `com.twenty.mocklocation`），
由 **to** 開發並於 Google Play 發行。

- **生效日期：** 2026-10-01
- **開發者：** to
- **聯絡信箱：** to30839642@gmail.com

---

## 一句話總結

這個 App 不收集、不上傳、也不販售你的位置。你建立的收藏與路線只存在你的裝置上。

---

## 一、本 App 不做的事

- **不收集你的位置。** 實際位置只在主動按下「裝置位置」時讀取一次，用來把地圖移到你所在的地方，讀完即用即丟，不會被儲存或傳送到任何伺服器。
- **沒有帳號。** 不需要註冊，不會要求 email、電話或任何身分資訊。
- **沒有分析工具。** App 內沒有任何行為分析、使用統計或崩潰回報 SDK。
- **不販售任何資料。**

## 二、資料儲存在哪裡

你在 App 內建立的所有內容——收藏地點、路線、標籤、App 設定——都以 Room 資料庫與 DataStore 儲存在**你的裝置本機**。開發者無法讀取。

若你在系統設定中開啟了 Android 的自動備份，這些資料會依 Android 的機制備份到你自己的 Google 帳戶。這是 Android 平台的功能，備份內容由 Google 依其政策處理，開發者同樣無法讀取。地圖圖磚快取已明確排除在備份與換機轉移之外。

你隨時可以在「設定 → 關於與備份」把收藏點、標籤、路線與 App 設定匯出成單一 JSON 檔，也可以把路線匯出成 GPX 檔。匯入時 App 會讀取你自己選取的檔案，內容只寫入本機資料庫，不會上傳。解除安裝 App 即刪除全部本機資料。

## 三、會離開裝置的網路連線

App 有四類對外連線，都是為了提供功能，且都不附帶你的身分：

| 連線對象 | 送出什麼 | 為什麼 |
|---|---|---|
| `tiles.openfreemap.org` | 目前地圖檢視範圍的座標 | 下載地圖圖磚才能顯示地圖 |
| Android 系統的地址查詢服務 | 你輸入的搜尋字串，或你選取的座標 | 地址搜尋與反查地址。此服務由裝置廠商提供，多數裝置上為 Google |
| 你貼上的地圖短網址所屬網域 | 該短網址本身 | 展開短網址以取得座標 |
| Google AdMob | 見下一節 | 顯示廣告 |

**關於 IP 位址：** 以上每一類連線都會讓連線的對方看到你的 IP 位址。這是網路本身的運作方式，不是本 App 額外送出的資訊，但它確實會離開你的裝置，所以列在這裡。

**關於短網址展開：** 展開時 App 會跟隨該網址的轉址鏈，最多六次，因此最終連到的網域可能不是你貼上的那一個。請求帶有一個固定的 User-Agent 字串，其中不含任何識別你的資訊。

## 四、廣告

本 App 使用 Google AdMob 顯示廣告。AdMob 為了投放與計算廣告，會收集**廣告 ID（Advertising ID）與裝置／使用資訊**，並與 Google 及其廣告合作夥伴共享。開發者本人不會收到這些資料的個別內容，只會看到彙總後的成效報表。

- Google 如何處理這些資料：<https://policies.google.com/technologies/partner-sites>
- 你可以在 Android 的「設定 → 隱私權 → 廣告」重設或刪除自己的廣告 ID，或關閉廣告個人化。
- App 內提供「移除廣告」：看完一支獎勵式廣告後，接下來 24 小時不顯示任何廣告；可以重複累加，最多累積 7 天。

**本 App 不會把你的位置資料提供給廣告服務。**

## 五、權限說明

| 權限 | 用途 |
|---|---|
| `ACCESS_FINE_LOCATION` / `ACCESS_COARSE_LOCATION` | 只在你按下「裝置位置」時讀取一次實際位置 |
| `ACCESS_MOCK_LOCATION` | Android 要求宣告此權限，App 才會出現在開發者選項的「選取模擬位置應用程式」清單中。它是一項選取資格，不是執行階段權限 |
| `INTERNET` / `ACCESS_NETWORK_STATE` | 下載地圖圖磚、查詢地址、展開短網址、顯示廣告 |
| `FOREGROUND_SERVICE` / `FOREGROUND_SERVICE_SPECIAL_USE` | 在你啟動模擬定位後，於前景服務中持續提供測試座標 |
| `POST_NOTIFICATIONS` | 顯示模擬定位的狀態通知與暫停／停止控制 |
| `WAKE_LOCK` | 僅在你選擇「熄屏連續續跑」時，於該期間保持 CPU 運作 |
| `com.google.android.gms.permission.AD_ID` | 讀取廣告 ID，用於投放與計算廣告 |
| `ACCESS_ADSERVICES_AD_ID` / `ACCESS_ADSERVICES_ATTRIBUTION` / `ACCESS_ADSERVICES_TOPICS` | 對應 Android Privacy Sandbox 的廣告介面 |

最後兩列由 Google 廣告 SDK 加入，不是 App 自己宣告的。

## 六、資料安全

你建立的資料不會離開你的裝置，因此開發者端沒有存放這些資料的伺服器或資料庫——沒有可以外洩的東西，因為沒有東西被收走。裝置上的資料由 Android 的應用程式沙箱保護，其他 App 無法讀取。

App 主動發出的連線中，地圖圖磚與廣告都走 HTTPS；展開短網址時採用你貼上的網址所指定的協定並跟隨其轉址。地址查詢由 Android 系統代為執行，其傳輸方式由系統與裝置廠商決定。

## 七、資料保存期限

開發者端不保存任何資料，因此沒有保存期限可言。

你在 App 內建立的資料保存在你的裝置上，直到你自行刪除或解除安裝為止。若你開啟了 Android 自動備份，該備份的保存期限依 Google 的政策處理，不在開發者的控制範圍內。

## 八、國際資料傳輸

地圖圖磚伺服器（OpenFreeMap）與 Google AdMob 的伺服器位於台灣境外，因此第三節列出的連線屬於跨境連線。這些連線不附帶可識別你的資訊，但如該節所述，對方會看到你的 IP 位址。

## 九、關於模擬定位這項功能本身

本 App 使用 Android 官方提供的開發者選項機制提供測試座標，**不會繞過應用程式對模擬定位的偵測**。是否接受模擬座標，由各個 App 自行決定。使用者需自行確認其用途符合所使用服務的條款。

## 十、兒童

本 App 並非針對 13 歲以下兒童設計，也不會刻意收集兒童的個人資料。

## 十一、歐盟使用者（GDPR）

本 App 在首次啟動時會透過 Google 的 User Messaging Platform 詢問廣告同意；在法規要求同意的地區（歐盟／歐洲經濟區、英國）會顯示同意表單。你可以拒絕；拒絕後仍會顯示廣告，但不會個人化。**在同意流程走完之前，App 不會向廣告伺服器發出任何請求。**

由於本 App 不收集可識別個人的資料、也沒有帳號，開發者端沒有可供你查詢、更正或刪除的個人資料。與廣告相關的資料權利請依上方 Google 的連結行使。

## 十二、美國使用者（CCPA／CPRA）

開發者本人不販售你的個人資料，也不會收到任何可識別你的資料。

本 App 使用 Google AdMob 投放廣告。在 CPRA 的定義下，為跨情境行為廣告而提供廣告 ID 可能構成「分享（share）」。你可以在 Android 的「設定 → 隱私權 → 廣告」關閉廣告個人化，或重設／刪除廣告 ID，以停止這種用途；也可以依第四節的 Google 連結行使相關權利。

## 十三、政策變更

本政策如有變更，會更新本頁面的生效日期。重大變更會一併於 App 更新說明中提及。

## 十四、聯絡

有任何疑問請寄至 **to30839642@gmail.com**。
