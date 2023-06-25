## 80. Remove Duplicates from Sorted Array II

* Link: [https://leetcode.com/problems/remove-duplicates-from-sorted-array-ii/](https://leetcode.com/problems/remove-duplicates-from-sorted-array-ii/description/?envType=study-plan-v2&envId=top-interview-150)
* Difficulty: medium

  <img width="671" alt="image" src="https://github.com/BCMoo/LeetCode/assets/29893605/86619c48-4afb-441e-984f-fcfb900e976c">

  <img width="685" alt="image" src="https://github.com/BCMoo/LeetCode/assets/29893605/6a59583d-2a4f-48d4-b659-492e4d9ce6ca">

  <img width="298" alt="image" src="https://github.com/BCMoo/LeetCode/assets/29893605/cd17f609-638a-42aa-abdf-9eaeda9a1bf3">

  
* Solution 
    * Solution 1
      * Idea
        * 因array為遞增，將某位置的數字和該位置往前兩個index的element相比，若該數字大於後者表示此數字出現未超過2次
      * Complexity (time / space) = O(n), O(1)
      * Code
     
        <img width="244" alt="image" src="https://github.com/BCMoo/LeetCode/assets/29893605/80867527-19b7-4f5b-bc38-1873350db4a1">

    
    




