## 26. Remove Duplicates from Sorted Array

* Link: https://leetcode.com/problems/remove-duplicates-from-sorted-array/
* Difficulty: easy

  <img src="https://user-images.githubusercontent.com/29893605/150507660-972856b2-3400-4931-b902-9b519f1ed59c.png" width="800" />
* Constraints

  <img src="https://user-images.githubusercontent.com/29893605/150973732-db1e604d-fee5-4b8f-83a0-285f015a9406.png" width="400" />


* Solution
  * Solution 1
    * Idea
      *  取unique後將nums前len(unique_num)的元素改為unique的list
    * Complexity (time / space) = O(n), O(n)
    * Code
      
      <img width="400" alt="image" src="https://github.com/BCMoo/LeetCode/assets/29893605/c4c75858-82e3-43de-ab0a-ad0eb6cbeaf4">


  * Solution 2 
    * Idea    
      <img src="https://user-images.githubusercontent.com/29893605/150643236-23b25522-52a2-4703-adf3-bf14ad22c716.png" width="600" />
    * Complexity (time / space) = O(n), O(1)
    * Code 

      <img src="https://user-images.githubusercontent.com/29893605/150508219-1981da69-7b0b-44a2-8410-382b71366abc.png" width="400" />
    * Key: 一個變數(i)紀錄填值位置，一個變數(j)紀錄比對位置

  * Solution 3

    * Idea  
      <img src="https://user-images.githubusercontent.com/29893605/150643312-5805a975-1966-4f55-83e5-11ca8a6ef21d.png" width="600" />
    * Complexity (time / space) = O(n), O(1)
    * Code

       <img src="https://user-images.githubusercontent.com/29893605/150525340-6d2ff65b-b719-4f98-9ed9-a3321d2c84f3.png" width="360" />

  * Solution 4

    * Idea  
      * Use pop
    * Complexity (time / space) = O(n), O(1)
    * Code
    
       <img width="300" alt="image" src="https://github.com/BCMoo/LeetCode/assets/29893605/e26861e0-5ec7-45f5-9dd2-7f330b11d1e0">

