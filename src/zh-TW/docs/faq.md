---
description: '關於使用 Misskey 時的常見問題。'
---

# 常見問題
本節是關於使用 Misskey 時的常見問題。<br>
關於 Misskey 專案本身的常見問題在[這裡](../misskey#%E3%82%88%E3%81%8F%E3%81%82%E3%82%8B%E8%B3%AA%E5%95%8F)。

## 有 Android/iOS 上的 App 嗎？
Misskey 專案不為移動作業系統開發原生應用程式，但是有一些第三方的應用程式。詳見[這裡](./apps)。<br>

然而，第三方應用程式對 Misskey 最新功能的支援可能會有所延遲，如果沒有特別的偏好，我們建議使用 Misskey Web。由於 Misskey Web 支援 PWA 模式，因此它也可以像原生 App 一樣運作。詳見[這裡](todo)。

## 可以使用 Mastodon 的 App 登入嗎？
Misskey 與 Mastodon 的 API 不相容，因此 Misskey 不能透過 Mastodon 的 Ap 或 web 客戶端使用，但有一些例外。<br>
請使用 Misskey 官方的 Web 客戶端 Misskey Web。

## misskey.io 是 Misskey 專案的官方伺服器嗎？
misskey.io 不是 Misskey 官方的伺服器，也不屬於 Misskey 專案。misskey.io 是泛用的、無特定主題的、很容易註冊以及最大的 Misskey 伺服器。

## 「Misskey」名稱的由來？
主要開發者 syuilo 在考慮名稱時，偶然間聽到 May'n 的歌曲『Brain Diver』，取自其歌詞。

## 要怎麼追蹤其他的 Misskey・Pleroma 伺服器、Mastodon 伺服器上的使用者？
從選單中選擇搜索，並按照以下格式輸入使用者帳戶。使用者帳戶由使用者名稱與所屬的伺服器或伺服器主機名稱所組成。不限於 Misskey，Mastodon 和 Pleroma 等多數的分散式軟體，以下的使用者帳戶格式是很常見的。<br>

使用者帳戶的格式：`@使用者名稱@Misskey・Pleroma 伺服器或 Mastodon 伺服器的主機名稱`<br>
使用者帳戶範例：`@syuilo@misskey.io`<br>

儘管使用者帳戶的格式並非所有的分散式軟體都相同，但是這種格式允許您追蹤執行各種分散式軟體的其他伺服器或其上的使用者。

## 如何刪除轉發？
點擊轉發的時間顯示旁的「...」，選擇「取消轉發」。<br>
關於轉發，詳見[這裡](../docs/features/note.html#renote)。

## 不想顯示貼文內 URL 的預覽
Misskey 自己的標記式語言 MFM (Markup language For Misskey) 具有停用 URL 預覽的語法。詳見 MFM 小抄。MFM 小抄可以在您所屬的伺服器上輸入以下的地址查閱：`https://您的伺服器主機名稱/mfm-cheat-sheet`

## 想要新增、編輯、刪除自訂表情符號
只有您所屬伺服器的管理者可以新增、編輯、刪除自訂表情符號。如果需要的話，請直接連絡伺服器管理者。

## 想要開發機器人
可以利用 Misskey API 開發 Bot。詳見[這裡](../docs/api)。

## 翻譯貼文的功能是使用哪個服務？
正在使用機器翻譯服務的 [DeepL 翻譯](https://www.deepl.com/)。

## 已經建立了伺服器，但是需要通知電信事業嗎？
### 短的答案
如果是出於商業目的經營，**需要**。否則**不需要**。

### 長的答案
根據[總務省的文件](https://www.soumu.go.jp/main_content/000477428.pdf)，「經營者」的定義是「透過提供服務，並收取對架費用以獲得收益者」。因此，非商業目的不需要通知。此外，據總務省的答覆，即使有捐贈等收入，如果不是經營目的（賺錢）則不屬於需要通知的經營者範疇。<br>
詳見總務省的[電信事業入門手冊](https://www.soumu.go.jp/main_content/000477428.pdf)等資料，或洽詢總務省。

## 發布名稱能否包含「Misskey」呢？
「Misskey」是 Misskey 的作者篠田英司 (syuilo) 截至 2022 年 11 月正在申請的商標 (2022-054788)。即使已註冊商標，發布名稱中帶有「Misskey」（例: Misskey Tools 等）服務也沒有問題。
此外，即使在那種情況下也沒有收取使用費的計畫。
