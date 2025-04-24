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
1) size ->> total number of nodes
2) child & parent
3) sibling -> having same parent
4) edge -> line connecting 2 nodes
5) height -> max number of edges between 2 nodes
