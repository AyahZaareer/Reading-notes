## What’s a Linked List?
### inked list is a linear collection of data elements whose order is not given by their physical placement in memory. Instead, each element points to the next. It is a data structure consisting of a collection of nodes which together represent a sequence>

#### The difference between arrays and linked lists :
- The fundamental difference between arrays and linked lists is that arrays are static data structures, while linked lists are dynamic data structures.
- A static data structure needs all of its resources to be allocated when the structure is created; this means that even if the structure was to grow or shrink in size and elements were to be added or removed, it still always needs a given size and amount of memory. 
- a dynamic data structure can shrink and grow in memory. It doesn’t need a set amount of memory to be allocated in order to exist, and its size and shape can change, and the amount of memory it needs can change as well.

### Parts of a linked list:
![image](https://user-images.githubusercontent.com/79833733/124067395-023abd00-da43-11eb-824e-19ec0445f4cd.png)


### There are three common types of Linked List:
- Singly Linked List
  - It is the most common. Each node has data and a pointer to the next node.
  ![image](https://user-images.githubusercontent.com/79833733/124068720-b3415780-da43-11eb-94fb-7b688d35b8f6.png)

  
- Doubly Linked List
   - We add a pointer to the previous node in a doubly-linked list. Thus, we can go in either direction: forward or backward.
     ![image](https://user-images.githubusercontent.com/79833733/124068853-f1d71200-da43-11eb-9d67-1ec2494b2101.png)


- Circular Linked List
  - A circular linked list is a variation of a linked list in which the last element is linked to the first element. This forms a circular loop.
   ![image](https://user-images.githubusercontent.com/79833733/124068945-10d5a400-da44-11eb-9c80-e8eaf1a4aea4.png)
### Terminology:
- **Linked List :**  A data structure that contains nodes that links/points to the next node in the list.
- **Singly :** refers to the number of references the node has. A Singly linked list means that there is only one reference, and the reference points to the Next node in a linked list.
- **Doubly :** refers to there being two (double) references within the node. A Doubly linked list means that there is a reference to both the Next and Previous node.
- **Node :** Nodes are the individual items/links that live in a linked list. Each node contains the data for each link
- **Next :** Each node contains a property called Next. This property contains the reference to the next node.
- **Head :** The Head is a reference of type Node to the first node in a linked list.
- **Current :** The Current is a reference of type Node to the node that is currently being looked at. When traversing, you create a new Current variable at the Head to guarantee you are starting from the beginning of the linked list.




## what even is Big O?
- Big O notation is a way to express the amount of time that a function, action, or algorithm takes to run based on how many elements we pass to that function.

#### type of Big O in Linked List:
- An O(1) function takes constant time, which is to say that it doesn’t matter how many elements we have, or how huge our input is: it’ll always take the same amount of time and memory to run our algorithm. 
- An O(n) function is linear, which means that as our input grows (from ten numbers, to ten thousand, to ten million), the space and time that we need to run that algorithm grows linearly.
