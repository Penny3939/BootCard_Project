# BootCard_Project
## 專案目標：
協助店家數位轉型，解決店家面臨人力短缺、營收不佳、管理不善等等問題，利用LINE Bot、機器學習、資料庫技術來建立完善推薦系統、庫存管理、報表分析。
> 開發LINE  Bot 、API串接，整合店家與顧客端服務。
> 使用GCP 來佈署專案。
> 運用MySQL建立資料庫。
> 透過Tableau分析商業數據。
> 利用模型、機器學習，建立推薦系統。

## 開發功能項目、解決方針:
(1) 提高客戶黏著度、滿意度：推薦系統、消費紀錄查詢、店鋪資訊功能。\
(2) 解決人力短缺問題：協助頁面、線上訂餐功能。\
(3) 行銷策略：優惠券、點數發放、顧客分群。\
(4) 解決營運方針：反饋問卷、庫存量警訊、銷售量預測。\
(5) 檢視營運財況：銷售紀錄、財務報表。

## 重點技術使用:
> LINE Bot API串接、機器學習、MySQL資料庫、爬蟲、Flask、GCP雲端架構。\
> 使用模型協同過濾方法進行SVD分解，以獲取矩陣特徵並進行模型訓練來建立完善推薦系統、結合Tableau設計出視覺化界面，進行財報、預測分析。
> 
> 推薦系統：\
目的 : 根據客戶過往喜好，提供客製化商品推薦，以增加客戶的滿意度。\
使用 「KNN、SVD」 ，使用模型協同過濾方法並進行SVD分解，以獲取矩陣特徵並進行模型訓練。

> 銷售量預測：\
目的 : 預測具有時效性產品，降低銷售成本，讓店家可提前作原物料準備。\
使用 「LSTM、GRU」預測未來銷售量及變化，並將結果利用Tableau視覺化呈現。\
![螢幕擷取畫面 2023-06-13 234429](https://github.com/Penny3939/BootCard_Project/assets/125810833/e8cfc9cb-caae-45f7-826c-ca04d582bf64)
![螢幕擷取畫面 2023-06-13 234449](https://github.com/Penny3939/BootCard_Project/assets/125810833/4b556284-7b9c-4038-be2d-49507b51bfc3)


## LINEBot架構圖:
![螢幕擷取畫面 2023-06-13 233910](https://github.com/Penny3939/BootCard_Project/assets/125810833/8d5414d3-04b1-460b-b3fe-b68239e8e086)\

## LINEBot 介面 
#### 顧客端介面：
![S__179822621](https://github.com/Penny3939/BootCard_Project/assets/125810833/e6a58c6c-8840-44c2-91c3-cdedbb226dca)
#### 商家端介面：
![S__179822619](https://github.com/Penny3939/BootCard_Project/assets/125810833/2aa45f4d-0315-4629-83c0-0d6895af48d9)

## 專案Demo影片:
https://drive.google.com/file/d/1WnFbQ913zDBLBif4lAqFSbxrNqHflzF6/view?usp=sharing

## 專案簡報:
https://drive.google.com/file/d/1Iwfhn4EeqaVf9BZyHTf3sxj0uNnnUtlw/view?usp=sharing
