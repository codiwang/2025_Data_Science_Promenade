# 永不下線的代價-探討數位工作型態對身心健康之衝擊
本研究旨在探討在數位化浪潮下，台灣在職者的工作型態對其身心健康的影響。我們使用「113 年數位近用調查」問卷數據，篩選出 6,664 份在職者有效樣本，並運用 Python 及 R 進行資料分 析，包含描述性統計、T 檢定、相關性分析，另外也建立總體與分年齡層的多元線性迴歸模型。 研究結果顯示，「下班後處理公事」此數位過勞的指標僅在年輕族群身上對「主觀幸福感」有顯 著的負面影響，在整體樣本中則未呈現顯著關聯。然而，整體而言此行為與「身體狀況惡化」存 在顯著關聯。另外亦發現，影響主觀幸福感的最強烈預測因子是個人的「身體狀況」。本研究的 結果可應用於企業規劃數位工作制度，並為個人在數位化時代追求身心健康提供參考方向，具 有極大的應用價值。

### 檔案目錄
- data113_1.csv: 原始資料檔案
- working_population_health_data.csv: 處理後資料檔案
- ques113_1.pdf: 問卷問題與答題選項說明
- data_preprocessing.ipynb: 資料預處理程式
- data_analysis.ipynb, digital_data_analysis.R: 資料分析程式

### 環境需求
Python 3.10+
主要套件：pandas, numpy, matplotlib, seaborn, scipy

### 程式執行
1. 先執行 data_preprocessing.ipynb 完成資料預處理，產出清理後的資料 working_population_health_data.csv。
2. 再執行 data_analysis.ipynb 與 digital_data_analysis.R 產出圖表與統計分析。

