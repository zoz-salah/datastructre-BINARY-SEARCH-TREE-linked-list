🌳 Binary Search Tree (BST) — C++ Implementation
📌 Overview

This project contains an implementation of a Binary Search Tree (BST) in C++ using dynamically allocated nodes (linked structure — not arrays).
A Binary Search Tree is a special type of binary tree where:

Every node has at most 2 children

Left subtree contains values less than the parent

Right subtree contains values greater than the parent

No duplicate values are stored

BSTs are very useful for:
✔ Searching
✔ Sorting
✔ Storing hierarchical data
✔ Fast insert / delete / search operations

⚙️ Features Implemented

This project supports the following operations:

🔹 Insert a node

Adds a value to the BST while maintaining order.

🔹 Search for a value

Checks whether a value exists in the tree.

🔹 Delete a node

Removes a value while keeping the BST valid:

Deletes leaf nodes

Deletes nodes with one child

Deletes nodes with two children

🔹 Tree Traversals

Three standard traversal methods are implemented:

Traversal	Order	Use Case
In-Order	Left → Root → Right	Sorted output
Pre-Order	Root → Left → Right	Tree copying
Post-Order	Left → Right → Root	Deleting tree
🧠 Time Complexity
Operation	Average	Worst Case
Insert	O(log n)	O(n)
Search	O(log n)	O(n)
Delete	O(log n)	O(n)

Worst-case happens when the tree becomes skewed (like a linked list).
