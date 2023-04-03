# READING NOTES 5

## Linked Lists:

A Linked List is a data structure composed of nodes that link to each other through references and it can be either singly linked or doubly linked.

Singly linked means that each node has one reference that points to the next node in the list, while doubly linked means that each node has two references, one pointing to the previous node and the other to the next node.

Traversing a linked list requires using a 'while loop' that relies on the Next property to move between nodes until it reaches the end. The Current variable indicates where in the linked list the program is, and it moves forward during traversal until the end is reached. The Includes method checks whether a specific value is present in the linked list.

The Big O of time for Includes is O(n), and the Big O of space is O(1).