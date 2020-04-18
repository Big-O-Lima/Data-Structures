
#LINKED LIST
by Jose Torres [@CoderPug](http://www.github.com/coderpug)

##Concepts
- List of elements not necessarily contiguous in memory.
- Flexibility to grow.

#### Singly-Linked list
- A data structure with a list of elements where each element (node) contains a value and a pointer reference to the next element. 
- Null value on the pointer means the end of the list.
- Allows only forward iterations.

![image](Source/Images/linked-list-01.png)

#### Doubly-Linked list
- A Singly-Linked list where each element (node) also contains a pointer reference to the previous element (node).
- Allows forward and backward iterations.

![image](Source/Images/linked-list-02.png)

## Cycles
- Happens when the 'last' element (node) of the list points to a previous element inside the list.
- Cause infinite loops.
- Approaches for solving this issue : 

![image](Source/Images/linked-list-03.png)

#### A
- Include a boolean value inside the element (node) definition.
- The boolean value indicates if the elements was previously visited.

#### B
- Use an algorithm that keeps multiple references and iterate over the list to check if at some point the references are the same.

## Operations
-

## Representation
- 

## Complexity
- Insert: O(1) / O(n)
- Remove/Deletion: O(1) / O(n)
- Lookup: O(n)

## Direct Applications
- As a real basic structure it can be used whenever grow flexibility in a list is required. i.e queues, stacks

## Problems

- Hackerrank: Cracking the Coding <https://www.hackerrank.com/challenges/ctci-linked-list-cycle>
- Hackerrank: Linked-lists <https://www.hackerrank.com/domains/data-structures/linked-lists>
- Leetcode: Reverse a Linked List - https://leetcode.com/problems/reverse-linked-list/
- Leetcode: Detect Cycle in a Linked List - https://leetcode.com/problems/linked-list-cycle/
- Leetcode: Merge Two Sorted Lists - https://leetcode.com/problems/merge-two-sorted-lists/
- Leetcode: Merge K Sorted Lists - https://leetcode.com/problems/merge-k-sorted-lists/
- Leetcode: Remove Nth Node From End Of List - https://leetcode.com/problems/remove-nth-node-from-end-of-list/
- Leetcode: Reorder List - https://leetcode.com/problems/reorder-list/

## Bibliography

- <https://en.wikipedia.org/wiki/List_of_data_structures>
- <https://www.hackerrank.com/topics/linked-lists>
- <https://www.teamblind.com/post/New-Year-Gift---Curated-List-of-Top-100-LeetCode-Questions-to-Save-Your-Time-OaM1orEU>


*I totally stole the images from HackerRank - <https://www.hackerrank.com/topics/linked-lists>*
