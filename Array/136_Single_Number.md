## 136. Single Number

* Link: https://leetcode.com/problems/single-number/
* Difficulty: easy

  <img src="https://user-images.githubusercontent.com/29893605/151661186-e015e9cb-7c5d-4d12-9623-a3e7d4950987.png" width="250" />
 
  
* Constraints

  <img src="https://user-images.githubusercontent.com/29893605/151661221-5e4c7fc8-4353-48fc-8bc7-49e8471152eb.png" width="750" />

  
* Solution 1
  * Idea  
    * 依序掃過list並用dictionary存取每一個list中的element出現過幾次，dictionary的key為element的值，value為出現次數
    * 若掃到已存於dictionary的element則將該對應的value加1，反之將element添加到dictionary中且令value為0
    
  * Code 

    <img src="https://user-images.githubusercontent.com/29893605/151661819-a9a1e9e4-eea0-498a-9a4b-b3f60d18ed33.png" width="500" />


* Solution 2
  * Idea  
    * 依序掃過list並用另外的list(res)來存取僅出現過一次的element
    * 若掃到已存於res中的element則將該數值從res移除，反之添加到res中
    
  * Code 

    <img src="https://user-images.githubusercontent.com/29893605/151661357-7cc56a5d-013e-4a33-981b-1ccadea022b2.png" width="500" />
    




