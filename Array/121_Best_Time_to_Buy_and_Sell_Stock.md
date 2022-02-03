## 121. Best Time to Buy and Sell Stock

* Link: https://leetcode.com/problems/best-time-to-buy-and-sell-stock/
* Difficulty: easy


  <img src="https://user-images.githubusercontent.com/29893605/150978334-bb21c6bf-164f-4974-84df-a5addd396252.png" width="700" />
* Constraints

  <img src="https://user-images.githubusercontent.com/29893605/150978392-6dbc65b1-dbee-4098-8fad-d3858d3bf3f9.png" width="250" />
  
* Solution 1
  * Idea  
    * 一個變數紀錄左邊隔板的index，一個變數紀錄右邊隔板的index 
    * 比較左右隔板的高度，較低者向內移動
    * 計算各種左右隔板組合下的max area of water直到左右相碰
    
  * Code 

    <img src="https://user-images.githubusercontent.com/29893605/152327839-a0dc3626-e5d4-4b55-869f-82d40d15cf38.png" width="780" />



