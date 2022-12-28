# 世界時鐘練習專案 Readme
WorldClock 

## 主要介紹
使用JavaScript日期函數，建立一目了然的世界時鐘，並有白天和黑夜的設計。

## DEMO link
[https://tomy5566.github.io/WorldClock/](https://tomy5566.github.io/WorldClock/)

## 使用技術
- HTML
- CSS: [flex](https://developer.mozilla.org/zh-CN/docs/Web/CSS/flex)
- JavaScript
- [setInterval() ](https://developer.mozilla.org/en-US/docs/Web/API/setInterval)

## JavaScript 使用技術介紹

1. 建立一個 JavaScript  [Date物件 ](https://developer.mozilla.org/zh-TW/docs/Web/JavaScript/Reference/Global_Objects/Date) 來指向某一個時間點。並回歸格林威治標準時間，換算毫秒等單位。
2. 建立不同城市的時區陣列，利用函數與上述校證的時間算出當地時間，日期，與星期。
3. 設計白天與黑夜的圖像介面，讓使用者一目了然該城市的狀況。
4. 使用  [setInterval() ](https://developer.mozilla.org/en-US/docs/Web/API/setInterval)讓每一秒均重新抓取資料，以及渲染到瀏覽器介面，創造電子鐘的感覺。
5. 利用 [Element.innerHTML](https://developer.mozilla.org/zh-TW/docs/Web/API/Element/innerHTML) 配合ES6  [Template literals](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Template_literals)建立城市時間卡片。並使用flex排列。
6. 利用for loop 的 [Object.entries() ](https://developer.mozilla.org/zh-CN/docs/Web/JavaScript/Reference/Global_Objects/Object/entries) 陣列帶入城市的資料，故往後若要新增新城市，只要更新陣列即可。

## 功能介紹
- 一目了然各大城市的日期，時間，以及星期的資訊。
- 利用黑色與黃色，讓使用者清晰分辨不同城市的黑夜與白天資訊。
- 自動更新時間，不須重整也能持續快速對時。

## 介面展示
![image](https://github.com/tomy5566/WorldClock/blob/main/DEMO_SEC_GIF.gif)


## 參考資料
六角學院JavaScrip 地下城 
