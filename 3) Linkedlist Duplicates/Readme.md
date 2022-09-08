# 82. Remove Duplicates from Sorted List II

Given the head of a sorted linked list, delete all nodes that have duplicate numbers, leaving only distinct numbers from the original list. Return the linked list sorted as well.

'''
Input: head = [1,2,3,3,4,4,5]
Output: [1,2,5]
'''

[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/82A7Je0dHFA/0.jpg)](https://www.youtube.com/watch?v=82A7Je0dHFA)

## Approach
We will use two pointers. Initially we create a dummy node and then check if the head.val is equal to head.next.val if so then we put the same statement in while loop and traverse the head then we point slow.next to head.next if head.val not equal to head.next.val then we simply traverse slow to slow.next