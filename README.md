# 0x1D. C - Binary trees

A binary tree is a tree data structure in which each parent node can have at most two children. Each node of a binary tree consists of three items:

data item

address of left child

address of right child

* Binary Tree Representation

A node of a binary tree is represented by a structure containing a data part and two pointers to other structures of the same type.
 struct node
{
 int data;
 struct node *left;
 struct node *right;
};

* Tree Terminologies

Node
A node is an entity that contains a key or value and pointers to its child nodes.

The last nodes of each path are called leaf nodes or external nodes that do not contain a link/pointer to child nodes.

The node having at least a child node is called an internal node.

Edge
It is the link between any two nodes.

Nodes and edges of a tree
Nodes and edges of a tree
Root
It is the topmost node of a tree.

Height of a Node
The height of a node is the number of edges from the node to the deepest leaf (ie. the longest path from the node to a leaf node).

Depth of a Node
The degree of a node is the total number of branches of that node.

Forest
A collection of disjoint trees is called a forest.

Forest in data structure
Creating forest from a tree
You can create a forest by cutting the root of a tree.

Tree Traversal

In order to perform any operation on a tree, you need to reach to the specific node. The tree traversal algorithm helps in visiting a required node in the tree.
