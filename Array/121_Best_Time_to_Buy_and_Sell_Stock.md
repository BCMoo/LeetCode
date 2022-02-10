## 121. Best Time to Buy and Sell Stock

* Link: https://leetcode.com/problems/best-time-to-buy-and-sell-stock/
* Difficulty: easy


  <img src="https://user-images.githubusercontent.com/29893605/150978334-bb21c6bf-164f-4974-84df-a5addd396252.png" width="700" />
* Constraints

  <img src="https://user-images.githubusercontent.com/29893605/150978392-6dbc65b1-dbee-4098-8fad-d3858d3bf3f9.png" width="250" />
  
* Solution 
  * Idea  
    * 一個變數紀錄最大獲利，一個變數紀錄買價 
    * 買價 = 現有買價與新價格相比較小者
    * 最大獲利 = 現有最大獲利與(新價格-買價)相比較大者
    
  * Code 

    <img src="https://user-images.githubusercontent.com/29893605/150978546-33708847-4e63-4e11-ac72-89f6ee9948be.png" width="500" />
