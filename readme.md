# 一天一英文

## Line Bot
- 回應: 輸入 **英文單字** 獲得一個新的隨機單字 
- 推播: 每日定時收到 LINE 訊息


## 資料來源
例句: [劍橋辭典](https://dictionary.cambridge.org/zht/)
音檔: [google translate](https://translate.google.com/)

## 心路歷程
1. 建立 Line bot
2. 使用 webhook 回應訊息
    - 架設於 vercel
3. 推播訊息
    - vercel 加入 cron job，定時自動推播
4. 建立單字庫 (excel file)
    - 爬蟲取得劍橋辭典的翻譯、例句、音檔
5. 繪製圖片
    - 將單字庫建立成圖片
    - 匯出，上傳至 github
6. 隨機選取
    - 挑選已完成的單字傳送
    - 傳送圖片、音檔
