# binary_trees

## 0x1D. C - Binary trees

### Binary Tree

A binary tree is a data structure consisting of nodes connected in a hierarchical manner. Each node can have at most two child nodes, commonly referred to as the left child and the right child. The nodes in a binary tree are organized in a way that allows for efficient searching, insertion, and deletion operations.

### Binary Tree vs. Binary Search Tree

The main difference between a binary tree and a Binary Search Tree (BST) lies in the ordering of the nodes. In a binary tree, there are no specific rules regarding the ordering of the elements. Each node can have any value and can be placed in any position within the tree. On the other hand, a Binary Search Tree follows a specific ordering property: for each node, all values in its left subtree are smaller, and all values in its right subtree are larger.

### Time Complexity Gain Compared to Linked Lists

In terms of time complexity, binary trees can provide significant gains compared to linked lists for certain operations. Searching, inserting, and deleting elements in a binary tree have an average time complexity of O(log n), where n is the number of nodes. This efficiency is achieved due to the hierarchical structure and the ability to discard half of the remaining nodes at each step. In contrast, linked lists have a linear time complexity of O(n) for these operations since all elements must be traversed.

### Depth, Height, and Size of a Binary Tree

- **Depth**: The depth of a node in a binary tree represents the number of edges from the root node to that particular node.
- **Height**: The height of a binary tree is the maximum depth among all its nodes. It represents the length of the longest path from the root to a leaf node.
- **Size**: The size of a binary tree refers to the total number of nodes present in the tree.

### Traversal Methods in Binary Trees

There are three commonly used traversal methods to go through the nodes of a binary tree:

1. **Inorder Traversal**: In this method, the left subtree is traversed first, followed by visiting the current node, and then the right subtree.
2. **Preorder Traversal**: The current node is visited first, followed by traversing the left subtree, and then the right subtree.
3. **Postorder Traversal**: The left subtree is traversed first, then the right subtree, and finally, the current node is visited.

### Complete, Full, Perfect, and Balanced Binary Trees

- **Complete Binary Tree**: A complete binary tree is a tree in which all levels, except possibly the last one, are fully filled, and all nodes are as left as possible. In the last level, the nodes are filled from left to right.
- **Full Binary Tree**: A full binary tree is a tree in which every node has either 0 or 2 children. In other words, each node is either a leaf node or an internal node with two children.
- **Perfect Binary Tree**: A perfect binary tree is both full and complete, meaning all levels are fully filled with the maximum number of nodes.
- **Balanced Binary Tree**: A balanced binary tree is a tree in which the difference between the heights of the left and right subtrees of any node is at most one. This property ensures that the tree remains relatively balanced, optimizing search and other operations.
