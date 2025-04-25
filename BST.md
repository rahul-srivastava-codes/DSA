Best way of accessing any element.
Suppose number is 10
enter 5 and 20
it goes to left side of 10
and 12 goes right side of 10

Limitation
1) Inefficient for sorted data
2) O(N) time in sorted case

Creating tree should start by creating node
class node{
int val;
node left;
node right;}
Is it similar to DLL , yes you got it. 
Now combine multiple nodes and you got tree

Properties
1) size -> total number of nodes
2) child & parent
3) sibling -> having same parent
4) edge -> line connecting 2 nodes
5) height -> max number of edges between 2 nodes

Types of binary tree
1) Complete binary tree -> All of them should be full or full from left to right
2) full / Strict binary tree -> either 2 or 2 children for every node
3) Perfect binary tree -> all levels are full
4) height balanced -> avg height O(log n)
5) skewed BT -> every tree have height O(n) like linked list
6) ordered BT -> every node has some property  ex -> BST

properties
1) Perfect BT  height = h
total nodes = 2^(h+1) - 1
2) Total number of leaf nodes in perfect BT = 2^h - 1


Implementation
1) Linnked representation
2) sequential -> using array (heap is implemented using this)
