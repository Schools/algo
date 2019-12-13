Binary Search Tree
==================

### What is BST?

Binary Search Tree, is a node-based binary tree data structure which has the following properties:

1. The left subtree of a node contains only nodes with keys lesser than the node’s key.
2. The right subtree of a node contains only nodes with keys greater than the node’s key.
3. The left and right subtree each must also be a binary search tree.
4. There must be no duplicate nodes.

### What types of implementation are possible?
1. Object Oriented or Struct Oriented Linked list based Implementation.
2. Array Based Implementation


### What type of sorting is better for BST?
Insertion Sort in the tree.


### What are the uses of BST?

Binary Search Tree is frequently used as one of the important datastructure for building best priorty queue implementation.
In a priority queue, the high priority element should be on the top of the tree.

There are various variants of BST like B+, Multi dimensional KDT, DKT (like used in elastic search for Reverse Indexing)

While Hashing maps infinite elements to finite space for quick search. Priority Queues are required for RUNTIME execution and to handle incoming jobs are tasks asynchronously.

### Why hashing should not be used for Handling Async task?
The requirement at hand is FIFO processing. Queue is a best solution intutively. FIFO should employ priority, searching the high priority element remains as a task.
We find Hashing to be attractive for Searching. Yet, if we double check the requirement, It is better to avoid Creating duplicate of all elements in the Queue creating HASHtable. BST and AVL Tree could do very well in this situation for space effeciency and the required rearragement will be taking very less time than searching in Hashtable.

Hashing is mainly used for caching and involves random arrangement of elements in hashtable. Hashing efficiency depends on the type of Hash Function.


### What are other Binary Search Trees Available?

http://www.differencebetween.info/difference-between-b-tree-and-b-plus-tree