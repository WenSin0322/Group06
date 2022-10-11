
## 專題題目 : 影像辨識-行車紀錄器
## 內容 : 設計一個影像擷取盒子：
    1.收集行車紀錄器影像資料。
    2.開發影像辨識截取系統辨識動物畫面。
    3.設計標籤系統，標記產品編號、時間、地點、寵物特徵。
    4.影像自動上傳至網路平台。


|Group06|Members|Works|
|:----:|:----:|:-----:|
|組長|C109118242洪偉錦|網站架設|
|組員|C109118207沈文鑫|硬體開發|
|組員|C109118241羅子謙|訓練模型開發|
|組員|C109118243廖哲寬|前端設計|
|組員|C109118247馮紀軒|後端架設|


**(1)PERT/CPM圖**
---
[PERT/CPM](https://hackmd.io/@el3TQc_2ScCsyXBi0HyyUQ/H1TWre7Qj)

![![來源]([https://hackmd.io/fKtHwO3BTU-joUJNl6rKsw?view](https://hackmd.io/@el3TQc_2ScCsyXBi0HyyUQ/H1TWre7Qj
))](https://user-images.githubusercontent.com/113969755/195119825-c6a9474d-c939-4898-8356-30e8592600c9.png)


**(2)甘特圖**
---
```mermaid
gantt
    title 甘特圖

    

    section 1.研擬計畫
    4       :a1,2022-10-11, 4d
   
    section 2.任務分配
    2       :a2, after a1  , 2d
    
    section 3.可行性認證
    10      :a3, after a1 , 10d
    
    section 4.程式開發
    25      :a4, after a2  , 25d
    
    section 5.硬體開發
    5      :a5, after a3  , 5d
    
    section 6.程式測試
    12      :a6, after a5  , 12d
    
    section 7.撰寫使用手冊
    8      :a7, after a8  , 8d
    
    section 8.轉換檔案
    2      :a8, after a4  , 2d
    
    section 9.系統測試
    15      :a9, after a8  , 15d
    
    section 10.使用者訓練
    20      :a10, after a8  , 20d
    
    section 11.使用者測試
    25      :a11, after a7  , 25d
