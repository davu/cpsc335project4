CPSC 335- Spring 2013
======================================
Project #4— minimum spanning trees
======================================
Introduction
======================================
In this project you will implement an efficient minimum spanning tree algorithm.
This involves implementing a graph representation and using an
appropriate data structure. The input graph will represent the layout of
the Disneyland resort.

Objective
=====================================
The goal is to implement one of the three minimum spanning tree (MST)
algorithms we’ve covered. Those three algorithms are
1. Prim’s algorithm, using only arrays and/or lists;
2. Prim’s algorithm, accelerated by a heap (a.k.a. priority queue); or
3. Kruskal’s algorithm, using the union-find data structure.
For full credit, you must implement one of the O(mlog n)-time MST algorithms
(2 or 3). If you cannot do this, you may instead implement algorithm
1, which is simpler but slower, running in O(mn) time. If you go this
route you will lose some credit, but still be eligible for credit on the other
parts of the project.
Our graph has n = 84 vertices and m = n(n􀀀1)
2 = 3; 486 edges. So all these
algorithms should finish very quickly if they are implemented properly.
