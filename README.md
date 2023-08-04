# C++ AVL Tree Implementation

This is a C++ implementation of an AVL tree, which is a self-balancing binary search tree. An AVL tree maintains the balance factor of each node, which is the difference between the heights of its left and right subtrees. Whenever a node becomes unbalanced (its balance factor is either -2 or 2), the tree performs a rotation to restore the balance.

## Features

This project provides the following features:

- Insertion: You can insert a new node with a given key and value into the AVL tree. The tree will automatically balance itself after the insertion.
- Deletion: You can delete an existing node with a given key from the AVL tree. The tree will automatically balance itself after the deletion.
- Search: You can search for a node with a given key in the AVL tree. The tree will return the value of the node if it exists, or null otherwise.
- Traversal: You can traverse the AVL tree in different orders, such as pre-order, in-order, post-order, or level-order. The tree will print the keys and values of each node during the traversal.
- Display: You can display the AVL tree in a graphical way, using parentheses to indicate the structure of the tree and the balance factors of each node.

## Usage

This project contains one file: main.cpp, which includes all the code and test cases for the AVL tree implementation. To compile and run the project, you can use the following commands:

```bash
g++ main.cpp -o avl_tree
./avl_tree
```
The output will show the results of each test case, such as the insertion, deletion, search, traversal, and display operations on the AVL tree.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
