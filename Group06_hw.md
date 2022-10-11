
## 專題題目 : 影像辨識-行車紀錄器
## 內容 : 設計一個影像擷取盒子：
    1.收集行車紀錄器影像資料。
    2.開發影像辨識截取系統辨識動物畫面。
    3.設計標籤系統，標記產品編號、時間、地點、寵物特徵。
    4.影像自動上傳至網路平台。


|Group06|Members|Works|
|:----|:----|:-----|
|組長|C109118242洪偉錦|網站架設|
|組員|C109118207沈文鑫|硬體開發|
||C109118241羅子謙|訓練模型開發|
||C109118243廖哲寬|前端設計|
||C109118247馮紀軒|後端架設|


**(1)PERT/CPM圖**
---
[PERT/CPM & 關鍵路徑]()




**(2)甘特圖**
---
```mermaid
gantt
    title 甘特圖

    

    section 1.研擬計畫
    1       :a1,2022-10-11, 1d
   
    section 2.任務分配
    4       :a2, after a1  , 4d
    
    section 3.取得硬體
    17      :a3, after a1 , 17d
    
    section 4.程式開發
    70      :a4, after a2  , 70d
    
    section 5.安裝硬體
    10      :a5, after a3  , 10d
    
    section 6.程式測試
    30      :a6, after a4  , 30d
    
    section 7.撰寫使用手冊
    25      :a7, after a5  , 25d
    
    section 8.轉換檔案
    20      :a8, after a5  , 20d
    
    section 9.系統測試
    25      :a9, after a6  , 25d
    
    section 10.使用者訓練
    20      :a10, after a7  , 20d
    
    section 11.使用者測試
    25      :a11, after a9  , 25d
