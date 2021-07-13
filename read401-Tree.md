# Trees:
## A tree is a nonlinear data structure, compared to arrays, linked lists, stacks and queues which are linear data structures. A tree can be empty with no nodes or a tree is a structure consisting of one node called the root and zero or one or more subtrees.

### The type of trees:
  - Binary Trees.
  - Binary Search Trees .
  - K-ary Trees

   ![image](https://user-images.githubusercontent.com/79833733/125485036-db8478d0-3f31-4c3b-a1a8-ba01cc4d7c54.png)


### Common Terminology:
  - **Node :** A Tree node is a component which may contain it’s own values, and references to other nodes
  - **Root :** The root is the node at the beginning of the tree
  - **K :** A number that specifies the maximum number of children any node may have in a k-ary tree. In a binary tree, k = 2.
  - **Left :** A reference to one child node, in a binary tree
  - **Right :** A reference to the other child node, in a binary tree
  - **Edge :** The edge in a tree is the link between a parent and child node
  - **Leaf :** leaf is a node that does not have any children
  - **Height :** The height of a tree is the number of edges from the root to the furthest leaf

### Traversals:
 - raversing a tree allows us to search for a node, print out the contents of a tree, and much more! There are two categories of traversals when it comes to trees:
    - **Depth First**
      - Depth first traversal is where we prioritize going through the depth (height) of the tree first. There are multiple ways to carry out depth first traversal, and each method changes the order in which we search/print the root. Here are three methods for depth first traversal:
       -  Pre-order: root >> left >> right
       - In-order: left >> root >> right
       - Post-order: left >> right >> root
    - **Breadth First**
      - Breadth first traversal iterates through the tree by going through each level of the tree node-by-node. So, given our starting tree one more time.
      - Traditionally, breadth first traversal uses a queue (instead of the call stack via recursion) to traverse the width/breadth of the tree. Let’s break down the process Given our starting tree shown above, let’s start by putting the root into the queue.






