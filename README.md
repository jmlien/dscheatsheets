# Data Structures Cheatsheet for CS 310

# Conceptural Representations

- Linear vs. Tree vs. Graph
- Linear structures are a subset of tree structures.
- Tree structures are a subset of graphs.

# Internal Representations

- Linked-List Based
  - Linear: queues, stacks, linked lists, separate chaining (HashSet, HashMap), deque
  - Tree: BST, AVL, Red-black, splay, B-tree, M-ary tree
  - Graph: adjacency list
  
- Array-List Based
  - Linear: circular queues, stacks, separate chaining (HashSet, HashMap), closed hashing, 
  - Tree: B-tree, heap (complete trees), union-find structure (disjoint sets), any tree structures (but will waste a lot of space)
  - Graph: adjacency matrix
  
 |   |Linear|Tree|Graph|
 |:-:| :-:|:-:|:-:|
 |Linked-list| | | |
 |Array-list| | | |

# Foundamental Operations

- Linear: add, remove, find, access, sort, merge
- Tree: add, remove, find, balance (ensuring a bound on the tree height), reducing tree to linear structures (traversal, sort), merge
- Graph: reducing graph to tree structures (MST, DFS, BFS, Shortest path tree, Spanning tree...), add/remove edges/vretices, merge (trivial), no sorting unless the graph is a DAG (so called topological sort or linearization of graph). 
  
## Other Cheatsheets 

- [Visualization of Algorithms and Data Structures](https://visualgo.net/en) from visualgo
- [BigO Cheatsheat](http://bigocheatsheet.com/img/big-o-cheat-sheet-poster.png) from http://bigocheatsheet.com/
- [Data Structure Cheatsheat](https://www.clear.rice.edu/comp160/data_cheat.html) from Rice U.
- [Algorithms and Data Structures Cheatsheet](https://algs4.cs.princeton.edu/cheatsheet/) from Princeton
- [Data Structures in Javascript](http://blog.benoitvallon.com/data-structures-in-javascript/data-structures-in-javascript/)
- [Data Structures](http://www.geeksforgeeks.org/data-structures/) from Geeks for geeks
- [Concise Notes on Data Structures and Algorithms](https://w3.cs.jmu.edu/spragunr/CS240_F12/ConciseNotes.pdf) in PDF, from JMU

## 
