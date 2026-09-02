# 零售交易資料分析：顧客分群與來店人數預測

以真實零售交易資料進行的完整分析專案，涵蓋資料清洗、顧客分群
（K-means）與來店人數的時序預測（RNN / LSTM）。

## 資料說明

原始交易資料因保密限制無法提供，本專案僅公開分析流程與方法說明。

- 資料類型：零售交易紀錄與會員資料
- 資料規模：（填：約 3億筆交易資料(實際分析2700萬筆)，時間範圍 2014/01 – 2016/10）

## 文件

分析過程與決策記錄在 `docs/`：

| 文件 | 內容 |
|------|------|
| [00_dataset.md](docs/00_dataset.md) | 資料來源、欄位定義與整體概況 |
| [01_transaction_cleaning.md](docs/01_transaction_cleaning.md) | 交易資料的清洗流程與判斷依據 |
| [02_member_cleaning.md](docs/02_member_cleaning.md) | 會員資料的清洗與整併 |
| [03_kmeans_analysis.md](docs/03_kmeans_analysis.md) | K-means 顧客分群：特徵設計、K 值選擇與分群結果 |
| [04_lstm_forecast.md](docs/04_lstm_forecast.md) | 來店人數預測：特徵工程、RNN 與 LSTM 的比較 |

## 目前狀態

程式碼整理中，近期補上。
