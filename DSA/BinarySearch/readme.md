# Daily Code Challenge - Binary Search

## Perfect Sequence
*Author: Matthew Petersen*

---

### Problem Domain

Binary search in a sorted 1D array, to find an integer. Return the index of which the integer is located or -1.

---

### Inputs and Expected Outputs

| Input | Expected Output |
| :----------- | :----------- |
| [1, 2, 3, 4, 5], 4 | 3 |


---

### Big O


| Time | Space |
| :----------- | :----------- |
| O(n) | O(n) |

Binary searches are great and fast for searching sorted arrays. First I set a left, middle and right variable. Then utilize a while conditional, checking if our left is < our right. This is to ensure our array is sorted. Next up, I check if our mid point is equal to our target integer. Lastly, another if statement is used to check if our mid point is greater than our target (or less). If so, we re-assign our left or right variable to be equal to the mid point +-1. These steps are repeated until 1 of these criteria are met: 

Mid point = target integer

Left variable > right variable (we never found our value)
---


### Whiteboard Visual
***[Your Whiteboard Image]***
![Image 1](../images/CC3.PNG)


---

### Change Log
No current changes at this time.  

---