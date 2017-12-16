# Data Structures Cheatsheet for CS 310

# Conceptural Representations

- Linear vs. Tree vs. Graph
- Linear structures include
  - Linked lists
  - Array lists
  - They are a subset of tree structures.
- Tree structures include 
  - Binary tree
  - Binary search tree
  - M-ary tree
  - Self-balance tree
    - AVL tree
    - Red-black tree
    - splay tree
  - B-tree
  - K-D tree, Range tree, Quad tree, Octree, interval tree, etc (we did not cover these in CS 310)
  - They are a subset of graphs.
- Graph structures include 
  - (Un-)Directed graph
  - (Un-)Weigted graph
  - Directed Acyclic graph (DAG)
  - Spare vs Dense graph
  - Bipartite graph (did not cover this in CS 310)
  - ... (many more)

# Internal Representations

- Linked-List Based
  - Linear: queues, stacks (mostly implemented as array list), doubly/singly linked lists, deque
  - Tree: BST, AVL, Red-black, splay, B-tree, M-ary tree
  - Graph: adjacency list
  
- Array-List Based
  - Linear: circular queues, stacks, closed hashing
  - Tree: B-tree, heap (complete trees), union-find structures (disjoint sets), any tree structure (but may waste a lot of space)
  - Graph: adjacency matrix
  
- Hybrid
  - separate chaining (HashSet, HashMap)
  

# Foundamental Operations

- Linear: 
  - add, remove
  - find, access
  - sort 
  - merge
  - Need to consider if the linear structure is sorted vs unordered 
- Tree: 
  - reducing tree to linear structures (traversal, sorting)
  - add, remove 
  - find, access
  - balance (ensuring a bound on the tree height)
  - merge 
  - For all of these operations, you need to consider if the tree is ordered (BST, B-tree) or unordered (binary tree, union-find)
- Graph: 
  - reducing graph to tree structures (MST, DFS, BFS, Shortest path tree, Spanning tree...), 
  - add/remove edges/vretices, 
  - merge (trivial), 
  - graph is mostly unordered so no sorting, unless the graph is a DAG (so called topological sort or linearization of graph). 
  
## Other Cheatsheets 

- [Visualization of Algorithms and Data Structures](https://visualgo.net/en) from visualgo
- [BigO Cheatsheat](http://bigocheatsheet.com/img/big-o-cheat-sheet-poster.png) from http://bigocheatsheet.com/
- [Data Structure Cheatsheat](https://www.clear.rice.edu/comp160/data_cheat.html) from Rice U.
- [Algorithms and Data Structures Cheatsheet](https://algs4.cs.princeton.edu/cheatsheet/) from Princeton
- [Data Structures in Javascript](http://blog.benoitvallon.com/data-structures-in-javascript/data-structures-in-javascript/)
- [Data Structures](http://www.geeksforgeeks.org/data-structures/) from Geeks for geeks
- [Concise Notes on Data Structures and Algorithms](https://w3.cs.jmu.edu/spragunr/CS240_F12/ConciseNotes.pdf) in PDF, from JMU

## 
