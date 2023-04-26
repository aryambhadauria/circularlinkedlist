 What is Circular linked list?
The circular linked list is a linked list where all nodes are connected to form a circle. In a circular linked list, the first node and the last node are connected to each other which forms a circle. There is no NULL at the end.

Circular Linked List 

There are generally two types of circular linked lists:

Circular singly linked list: In a circular Singly linked list, the last node of the list contains a pointer to the first node of the list. We traverse the circular singly linked list until we reach the same node where we started. The circular singly linked list has no beginning or end. No null value is present in the next part of any of the nodes.
 ![image](https://user-images.githubusercontent.com/125942960/234488092-5a0bb2df-b96e-44e2-9871-2570b18aa9a1.png)


Representation of Circular singly linked list

Circular Doubly linked list: Circular Doubly Linked List has properties of both doubly linked list and circular linked list in which two consecutive elements are linked or connected by the previous and next pointer and the last node points to the first node by the next pointer and also the first node points to the last node by the previous pointer.

Representation of circular doubly linked list

Note: We will be using the singly circular linked list to represent the working of the circular linked list.
![image](https://user-images.githubusercontent.com/125942960/234488173-9a576c9d-20cc-449d-b2ff-d28b6223994c.png)
