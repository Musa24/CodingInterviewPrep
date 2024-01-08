# CodingInterviewPrep

   1. **Detecting a Cycle in a Singly Linked List:**

      *Easy*  

      Given a singly linked list, write a function which takes in the first node in a singly linked list and returns a boolean indicating if the linked list contains a "cycle".
      A cycle is when a node's next point actually points back to a previous node in the list. This is also sometimes known as a circularly linked list.

      ```python
      #example 1
      #Input:  [A -> B, B -> C, C -> D, D -> E, E -> B]
      #Output: True

      #example 2
      #Input:  [1 -> 2, 2 -> 3, 3 -> 4, 4 -> null]
      #Output: False

      class Node:
        def __init__(self,value):
           self.value = value
           self.next = None

      #Solution

      def has_cycle(head):
         # your code
      
      ```
      Click [here](https://github.com/Musa24/CodingInterviewPrep/blob/main/python/linked_list/has_cycle.py) to view the code Snapshot
