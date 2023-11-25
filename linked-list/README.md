_Difficulty: Easy_

### Problem 1

## Delete node in a linked list

There is a singly-linked list <span style='color: red;'>head</span> and we want to delete a <span style='color: red;'>node</span> node in it. You are given the node to be deleted <span style='color: red;'>node</span>. You will not be given access to the first node of <span style='color: red;'>head</span>. All the values of the linked list are unique, and it is guaranteed that the given node <span style='color: red;'>node</span> is not the last node in the linked list.
Delete the given node. Note that by deleting the node, we do not mean removing it from memory. We mean:

- The value of the given node should not exist in the linked list.
- The number of nodes in the linked list should decrease by one.
- All the values before <span style='color: red;'>node</span> should be in the same order.
- All the values after <span style='color: red;'>node</span> should be in the same order.

### Example and Output

input: **head** = [4,5,1,9], **node** = 5 </br>
output: [4,1,9] </br>
explaination: You are given the second node with value 5, the linked list should become 4 -> 1 -> 9 after calling your function.

input: **head** = [4,5,1,9], **node** = 1 </br>
output: [4,5,9] </br>
explaination: You are given the third node with value 1, the linked list should become 4 -> 5 -> 9 after calling your function.

### Problem 2

## Remove nth node from end of list

Given the <span style='color: red;'>head</span> of linked list, remove the <span style='color: red;'>nth</span> node from the end of the list and return its head.

### Example and Output

input: **head** = [1,2,3,4,5], **n** = 2 </br>
output: [1,2,3,5] </br>

input: **head** = [1], **n** = 1 </br>
output: [] </br>

input: **head** = [1,2], **n** = 1 </br>
output: [1] </br>

### Problem 3

## Reverse linked list

Given the <span style='color: red;'>head</span> of a singly linked list, reverse the list, and return the reversed list.

### Example and Output

Input: **head** = [1,2,3,4,5] </br>
Output: [5,4,3,2,1] </br>

Input: **head** = [1,2] </br>
Output: [2,1] </br>

Input: **head** = [] </br>
Output: [] </br>
