## 630. Course Schedule III

* Link: https://leetcode.com/problems/course-schedule-iii/
* Difficulty: hard

<img src="https://user-images.githubusercontent.com/29893605/175783401-a3c4f9b0-a16a-47da-a399-3dadc004ac56.png" width="520" />


   <img src="https://user-images.githubusercontent.com/29893605/175553127-fbf3415e-0bd5-4142-89ba-d1453ccb6718.png" width="520" />
* Constraints

  <img src="https://user-images.githubusercontent.com/29893605/175553843-55285df4-6dd3-48d8-a3c7-6adce19b89a2.png" width="300" />

  
* Solution 
  * Idea  
    * 修課期限短的課程優先安排(較不急的課程慢慢安排)
    * 由修課期限短至長的課程依序檢視，看看若修了該門課預計完成的日期會不會超過課程要求的日子，若超過則將已選定要修的課程中所需修課天數最長的課程移除

  * Hint
    * 使用最小堆積的heap(樹上最小的元素永遠會在根節點 heap[0] 上) 
    
  * Code 
    
    <img src="https://user-images.githubusercontent.com/29893605/175559188-be71624d-16fb-45bb-8d60-fff16ee85ac9.png" width="600" />





