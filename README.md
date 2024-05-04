**DOCUMENTATION  OF THE LINKED LIST IS GIVEN BELOW:**

**LINKED LIST:**
Linked lists are one of the fundamental linear data structures alongside stacks, queues, arrays, and lists.
A linked list is a continuous list of nodes where a node is a block structure housing the node value and a pointer (or memory) address to the next node. Each node from the head node has a next pointer that keeps the address of the next node till it gets to the last node, which points to nothing.
Linked lists are used in web browsers to keep track of web pages visited and moves in multi-player board games. Linked lists also find usage in implementing other linear data structures and graphs, dynamic memory allocation, and performing arithmetic operations on long integers.

The connection from one node to another node differentiates linked lists from a regular list or array. Unlike the linked lists, arrays don’t keep track of their next or other values.

Here is a visual representation of a linked list:

A linked list with 4 nodes. Each node points to another node.
The last node always points to NULL, except for circular linked lists.
A linked list with 4 nodes. Each node points to another node.The last node always points to NULL, except for circular linked lists.
Types of Linked Lists

The last node always points to NULL, except for circular linked lists.
Types of Linked Lists
There are three types of linked lists:

**1)Singly-linked list
2)Doubly linked list
3)Circular linked list**

You can derive other linked lists from the basic ones, e.g., circular doubly linked lists. This article teaches you how to implement the singly and doubly linked list and briefly discusses the circular linked list.

Singly-linked list
You’re tasked with building a tool to retrieve documents connected to each other but stored at random memory locations. You’re puzzled as to what data structure to use to fit this use case, as arrays store documents sequentially. The good news is that you can use the singly linked list for this task.
Singly-linked list operations
The primary operations of a singly linked list include:

**1)Traversal
2)Insertion
3)Deletion**

**1)Traversal:**
In simple words, traversal is a process of accessing elements stored in an object. A traversal operation is executed to print the elements in a linked list. 

**2)Insertion:**
The insertion operation enables you to add nodes to your linked list. You can add nodes to your linked list by prepending the node, appending the node, or by adding nodes at specific positions in the linked list.

**_Prepending a node:_**
The prepend method adds a new node at the head of the linked list, making it the new head node. The previous head node is automatically set as the next node after the new node. 

**3)Deletion:**
The deletion operation involves removing a node from the linked list either from the head, tail or at a specified position. 
n the code block above, the delete_node function performs three delete operations:
Deleting the head node: If the position specified is 1, the head node is deleted by setting the value of the head node to the second node in the linked list.
Deleting the tail node: If the position specified equals the number of nodes present in the linked list, the linked list is traversed to the end, and the second to the last node’s pointer is set to None to eliminate the tail node.
Deleting a different node: If the position doesn’t match the head or tail nodes, the linked list is traversed until the specified position is reached. The node preceding the node at the specified position will have its next pointer set to the node located after the deleted node.

**Doubly linked list operations**
Just as before, the primary operations of a doubly linked list include:

**i)Traversal
ii)Insertion
iii)Deletion
**

**Circular linked lists**
  Circular linked lists are singly linked lists except that their last node points to the first node as opposed to None. As a result, the circular linked list does not have a tail node. Circular linked lists are commonly used to manage computing resources.
The circular linked list’s last node’s next pointer is set to the first node’s address.
The circular linked list shares the same logic for insertion, traversal, and deletion as the singly linked list with the only difference being the assignment of the last node’s next pointer to the head node.
