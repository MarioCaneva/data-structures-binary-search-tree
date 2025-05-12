# 🌳 Binary Search Tree (BST) in Python

This project demonstrates how to implement a Binary Search Tree (BST) — a common hierarchical data structure used to maintain sorted data for fast insertion, lookup, and deletion.

## What It Does

The custom `BinarySearchTree` class supports:
- `insert(key)`: Adds a node with the given value
- `search(key)`: Finds and returns the node (or `None`) if it exists
- `delete(key)`: Removes a node and restructures the tree as needed
- `inorder_traversal()`: Returns a sorted list of all nodes in ascending order

## Example

bst = BinarySearchTree()
nodes = [50, 30, 20, 40, 70, 60, 80]

for node in nodes:
    bst.insert(node)

print("Search for 80:", bst.search(80))
# Output: TreeNode with key 80

print("Inorder traversal:", bst.inorder_traversal())
# Output: [20, 30, 40, 50, 60, 70, 80]

⚙️ Key Concepts
- TreeNode class with left/right children

- Recursive search and insert logic

- Deletion with 3 cases (leaf, one child, two children)

- In-order traversal to extract sorted values

🔧 Tech Used
Python 3

Object-oriented programming

Recursion

🎯 This project is part of the foundational Data Structures series.
