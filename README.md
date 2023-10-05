Project Title: C - Binary Trees.

Overview

You are welcome to the C - Binar Trees Project. This team project will introduce you to the world of Binary Trees and its relevance in computer science. This project is suitable for beginners and professionals.


Key Topics Covered:

1. Binary Tree
	- Learn the Basics of what defines a binary tree and its hierachichal structure.

2. Binary Tree vs Binary Search Tree(BST)
	- Understand the key distinction between a Binary Tree and a Binary Search Tree(BST) and when to use each of them.

3. Time Complexity Advantage.

	- Explore the potential gains interms of time compkexity when using Binary Trees over linked lists for specific operations. 

4. Tree properties

	- Discover essential properties of Binary Trees, including depth, height, and size, and how these metrics affect performance. 

5. Traversal Method

	- Master various traversal techniques like inorder, preorder, and postorder to navigate and manipulate Binary Tree effectively.

6. Types of Binary Trees

	- Dive into the concept of full, complete, perfect, and balance binary trees, gaining insights into their characteristics and used cases.

with this detailed guide, you will gain the knowledge and experience on Binary trees and how it works with data structure and alogrithm.

Happy coding!


ompliance to Syntax and Compilation Error.

1. we will use betty style. It will be checked using betty-style.pl and betty-doc.pl for syntax error. 


2. All your files will be compiled on Ubuntu 20.04 LTS using gcc, using the options -Wall -Werror -Wextra -pedantic -std=gnu89


Header File

Make sure to include the binary_trees.h header file in your project, which should contain the prototype for the Binary tree node function.

Task 0 New node

Creating a new node:

start by calling the binary tree node function, passing the parent node and value that are needed to assigned to the new node.

For example:

binary_tree_t *createnewNode = binary_tree_node(parent, 42); 

This code create a new  node   with  the value of 42 and attachws it to a parent node.

Handling Failure:

• It's essential if your Your function must return a pointer to the new node, or NULL on failure

Working with the new  node  


Once you have a pointer to the newly created node, you can manipulate the binary tree by attaching it to other nodes as left or right children or using it in various binary tree e alogrithm

• However,  for this particular task, the created node does not have any child..


Task 1

Insertinng a left child node in a Binaryy   tree   - C The 'binary_tree_insert_left`, designed to insert a new node as the left child of an existing node within a binary tree. This will manipulate the binary tree data structure and expand it
This is the prototype below
binary_tree_t *binary_tree_insert_left(binary_tree_t *parent, int value); 

Parameters:

- `parent`: A pointer to the node to insert the left-child in
- `value`: The value to store in the new left child node.

Return Value:
- The function returns a pointer to the newly created node.
- In case of failure or if `parent` is `NULL`, it returns `NULL`. 

How to Use `binary_tree_insert_left` 

1. Include the Header File 

2. Insert the New Left Child**
3. Replacing Existing Left Child
4. Check both syntax and compilation error 

   NOTE: If the `parent` node already has a left child, the new node will take its place, and the old left child will become the left child of the new node.

Task 2
Inserting a Right Child Node in a Binary Tree - C Function 

The `binary_tree_insert_right`, designed to insert a new node as the right child of an existing node within a binary tree. This will expand the binary tree's right data structure and also manipulate it.  Below, you'll find a concise description of how to use this function effectively.

binary_tree_t *binary_tree_insert_right(binary_tree_t *parent, int value);
```
Parameters:
- `parent`: A pointer to the node where the new right child will be inserted.
- `value`: The value to store in the new right child node. 

Return Value:
• - Your function must return a pointer to the created node, or NULL on failure or if parent is NULL 

• If parent already has a right-child, the new node must take its place, and the old right-child must be set as the right-child of the new node.

