## 11. Container With Most Water

* Link: https://leetcode.com/problems/container-with-most-water/
* Difficulty: medium


  <img src="https://user-images.githubusercontent.com/29893605/152327233-e41fe699-ce3a-47c6-9b79-63f5c0884b6d.png" width="650" />
* Constraints

  <img src="https://user-images.githubusercontent.com/29893605/152327337-b321e149-cd2f-41b8-bad0-c57a85953fa3.png" width="210" />
  
  
* Solution 
  * Idea  
    * 一個變數紀錄左邊隔板的index，一個變數紀錄右邊隔板的index 
    * 比較左右隔板的高度，較低者向內移動，兩格板等高則兩者均向內移動
    * 計算各種左右隔板組合下的max area of water直到左右相碰
    <br>
    <br>
    <img src="https://user-images.githubusercontent.com/29893605/154813680-6156e1eb-2386-4f7f-8ac8-37c7aaf0890e.png" width="780" />
    <img src="https://user-images.githubusercontent.com/29893605/154813694-7c2cc256-aff2-420f-b17a-b1cafab07059.png" width="780" />
    <img src="https://user-images.githubusercontent.com/29893605/154813717-7503e43c-0d26-4ba9-b917-4e49382f450b.png" width="780" />
    <img src="https://user-images.githubusercontent.com/29893605/154813762-6c687fc6-32b7-4a59-9e2f-d72a3f796ef2.png" width="780" />
    

    
  * Code 

    <img src="https://user-images.githubusercontent.com/29893605/152327839-a0dc3626-e5d4-4b55-869f-82d40d15cf38.png" width="780" />
    
    




