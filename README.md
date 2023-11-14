# MNH_Monster_Notice_Board

以 Monster Hunter Now 的活動遊玩體驗為發想

用 Vue 搭配 Google Sheet 的 Side Project

###功能介紹

主要功能是讀取使用者所在座標（需要使用者點選許可）並根據座標位置顯示附近（30 km）的魔物列表，而魔物列表需要各位使用者一同回報建立

1. 點擊「上傳圖標（右邊第二個）」可以上傳魔物情報
2. 點擊「搜尋圖標（右邊第一個）」可以尋找附近 30 km 內的魔物情報（顯示順序依照玩家所在地為中心，根據魔物距離由近至遠）
3. 點擊「漏斗圖標（左邊第二個）」可以根據所選選項篩選清單
3. 顯示的魔物情報點擊「鎖定座標」會開啟新視窗於 google map 上顯示經緯座標
4. 點選右上角的「Ｘ」將取消顯示並且資料庫會增加移除數量
5. 點選「討伐完成」將取消顯示並且資料庫增加狩獵數量
6. 情報底部的長條圖為魔物討伐率，數值越高代表越多使用者回報討伐成功
***
v0.941 版本更新
1. 加入評分機制：取消顯示回報負評、討伐完畢回報好評
2. 修正預設魔物情報為無
***
v0.931 版本更新
1. 增加周目 6、星數 10
2. 使用者本人發布的魔物情報將直接過濾不會顯示在搜尋結果上
***
v0.93 版本更新
1. 按鈕改為圖標顯示
2. 發布畫面的周目、星數、魔物改為圖示
3. 搜尋結果的星數改為圖示
4. 加入篩選功能（魔物名、周目、星數）
5. 調整搜尋結果僅限 30 km 內魔物
***
v0.92 版本更新
資料庫加入活動資訊頁面，活動期間自動調整為 1 hr 刷新
***
v0.911 版本更新
1. 鎖定座標無效
2. 上傳情報確認
3. 上傳情報紀錄（魔物名、周目、星數將自動代入上次上傳時的數據）
***
v0.91 版本更新
1. 調整資料表
2. 情報公園標示
3. 加入按鈕提醒功能

[google 資料庫連結](https://docs.google.com/spreadsheets/d/1z4vV88d9-MQvJNsDI0YF3x1amLOso8bPlwFBYkfOsKo/edit?usp=sharing)