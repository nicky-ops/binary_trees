# 0x1D. C - Binary trees
## Learning Objectives
At the end of this project, you are expected to be able to explain to anyone, without the help of Google:

### General
* What is a binary tree
A binary tree is a tree data structure in which each node has at most two children, referred to as the left child and the right child.
A recursive definition using set theory is that a binary tree is a tuple (L, S, R), where L and R are binary trees or the empty set and S is a singleton set containing the root.

#### Types of binary trees
* Rooted binary trees
* Full binary tree
* Perfect binary tree
* A complete binary tree
* A balanced binary tree
* A degenerate tree

* What is the difference between a binary tree and a Binary Search Tree
A binary tree is a tree data structure in which each node has at most two children, commonly referred to as the left child and the right child. These nodes are connected in a hierarchical structure. Binary trees can be structured in various ways and may not necessarily have any specific order or arrangement of values in their nodes.

On the other hand, a Binary Search Tree (BST) is a specific type of binary tree where the nodes are organized in a particular way. In a BST, for any given node:

1. The left subtree of a node contains only nodes with values lesser than the node's value.
2. The right subtree of a node contains only nodes with values greater than the node's value.
3. Both the left and right subtrees of the node must also be Binary Search Trees.
4. This unique arrangement in a BST allows for efficient searching, insertion, and deletion operations. The BST's structure enables faster lookup times compared to a regular binary tree in certain scenarios because it imposes a specific ordering of elements within the tree.

* What is the possible gain in terms of time complexity compared to linked lists


* What are the depth, the height, the size of a binary tree
In a binary tree, the depth refers to the level of a node within the tree. The depth of the tree itself is the maximum depth of any node in the tree, usually measured by the number of edges from the root node to the furthest leaf node.
The height of a binary tree is the number of edges on the longest path from the root node to a leaf node. Alternatively, it can be described as the number of levels in the tree.
The size of a binary tree is the total number of nodes present in the tree.

* What are the different traversal methods to go through a binary tree
Pre-order, in-order, post-order, depth-first order, and breadth-first order, 
* What is a complete, a full, a perfect, a balanced binary tree
A *Complete binary tree* is a binary tree in which every level, except possibly the last, is completely filled, and all nodes in the last level are as far left as possible.
A *full binary tree* is a tree in which every node has either 0 or 2 children.
A *perfect binary tree* is a binary tree in which all interior nodes have two children and all leaves have the same depth or same level.
A *balanced binary tree* is a binary tree structure in which the left and right subtrees of every node differ in height by no more than 1.
