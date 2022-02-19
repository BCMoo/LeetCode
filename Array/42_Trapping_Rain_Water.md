## 42. Trapping Rain Water

* Link: https://leetcode.com/problems/trapping-rain-water/
* Difficulty: hard

  <img src="https://user-images.githubusercontent.com/29893605/154783224-08073d9f-c952-4b56-a057-4a11ebaa7021.png" width="550" />

* Constraints

  <img src="https://user-images.githubusercontent.com/29893605/154783210-cdd8bfb0-94fd-4489-bae4-4c07ef31e0d1.png" width="210" />

  
* Solution 
  * Idea 
    * 要知道每一個位置左方隔板的最大高度(max_left)和右方隔板的最大高度(max_right)
    * 每個位置的積水量 = min(max_left, max_right) - 該位置高度，若為負值則該處積水量為0
    
  * Code 1: 暴力法(time limit exceeded)
    * 依序在每個位置
  
    <img src="https://user-images.githubusercontent.com/29893605/154783549-8dfea219-3567-4b50-86d1-1db1a6b37255.png" width="500" />

  * Code 2
    * 將每個位置的左方隔板最大高度(max_left)和右方隔板最大高度(max_right)各以一個array記錄下來
    * 依序計算各個位置的積水量並相加
 
    <img src="https://user-images.githubusercontent.com/29893605/154783746-b9a96f8d-dc5a-4533-8f41-f8d73c6d9f79.png" width="680" />
    
  * Code 3: 雙指針法
    * 左右兩端各設置一個的指針
    * 使用max_left和max_right紀錄兩個指針走過的地方的最大值
    * 指針向內移動，每次移動max_left和max_right值較小的指針，直到兩個指針相遇

    <img src="https://user-images.githubusercontent.com/29893605/154784180-16dd4134-96a3-48a2-804b-05cb1a070f52.png" width="900" />
    
