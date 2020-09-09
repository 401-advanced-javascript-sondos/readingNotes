## Linked Lists

A Linked List is a sequence of Nodes that are connected/linked to each other. The most defining feature of a Linked List is that each Node references the next Node in the link.

* There are two types of Linked List - Singly and Doubly. We will be implementing a Singly Linked List in this implementation.
<br><br>

#### Elements of Lists
  - **Node :** the individual items/links that live in a linked list. Each node contains the data for each link.
  - **Next :** Each node contains a property called Next. This property contains the reference to the next node.
  - **Head :** The Head is a reference type of type Node to the first node in a linked list.
  - **Current :** The Current reference is a reference type of type Node that is currently being looked at.

<br><br>

#### How do we treverse linked lists?
  - When traversing a linked list, we depend on the `Next` value in each node to guide us `where the next reference is pointing`. 

  - The best way to approach a traversal is through the use of a **`while()`** loop. This allows us to continually check that the Next node in the list is not null.
  
  - When traversing through a linked list, the Current node is the most helpful. The Current will tell us where exactly in the linked list we are and will allow us to move/traverse forward until we hit the end.

<br><br>

## Memory management
<br><br>

![img](https://miro.medium.com/max/875/1*Xokk6XOjWyIGCBujkJsCzQ.jpeg)