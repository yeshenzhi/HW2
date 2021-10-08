# HW2
##甘特圖
```mermaid
gantt
    title A Gantt Diagram
    section 甘特圖
    研究企劃           :a1, 2014-01-01, 1d
    任務分配           :after a1, 4d
    取得硬體           :after a1, 17d
    程式開發           :after a2, 70d
    安裝硬體           :after a3, 10d
    程式測試           :after a4, 30d
    撰寫使用手冊       :after a5, 25d
    轉換檔案           :after a5, 20d
    系統測試           :after a6, 25d
    使用者訓練         :after a7 a8, 20d
    使用者測試         :after a9 a10, 25d
   
