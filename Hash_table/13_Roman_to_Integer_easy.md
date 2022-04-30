## 13. Roman to Integer

* Link: https://leetcode.com/problems/roman-to-integer/
* Difficulty: easy

  <img src="https://user-images.githubusercontent.com/29893605/165087376-941a0f36-1eb1-4bb7-8892-7d82fba4594d.png" width="500" />
  <img src="https://user-images.githubusercontent.com/29893605/166114942-1242febe-7ca4-4519-a196-5903608a1a87.png" width="500" />
  <img src="https://user-images.githubusercontent.com/29893605/165086320-78453ebe-e351-4653-8b1c-552c0d465bbe.png" width="500" />

  

 
* Constraints

  <img src="https://user-images.githubusercontent.com/29893605/165086535-b46e5fdd-4931-4899-972e-cdb4f49f909c.png" width="500" />
  

  
* Solution 
  * Idea  
    * 將羅馬字串由左到右兩兩相比，若位置在前的符號比位置在後的符號所代表的數字還小，表示前者需要被後者減去，反之則為加上
    * <img src="https://user-images.githubusercontent.com/29893605/166115371-a00c089f-c005-4f7c-99e8-49987f85a61d.png" width="600" />

  * Code    
    <img src="https://user-images.githubusercontent.com/29893605/165090150-8180c83d-6c17-488d-a18b-9071725f6509.png" width="650" />
    * 別忘了要確認該文字是不是字串的最後一個



