## 42. Trapping Rain Water

* Link: https://leetcode.com/problems/trapping-rain-water/
* Difficulty: hard

  <img src="https://user-images.githubusercontent.com/29893605/154783224-08073d9f-c952-4b56-a057-4a11ebaa7021.png" width="650" />

* Constraints

  <img src="https://user-images.githubusercontent.com/29893605/154783210-cdd8bfb0-94fd-4489-bae4-4c07ef31e0d1.png" width="210" />

  
* Solution 
  * Idea  
    * 一個變數紀錄左邊隔板的index，一個變數紀錄右邊隔板的index 
    * 比較左右隔板的高度，較低者向內移動
    * 計算各種左右隔板組合下的max area of water直到左右相碰
    
  * Code 

    <img src="https://user-images.githubusercontent.com/29893605/152327839-a0dc3626-e5d4-4b55-869f-82d40d15cf38.png" width="780" />
    
    
