# Computer Science Terminology

## Core Concepts

### Data Structures
- **Array**: Contiguous memory block; O(1) random access by index
- **Linked List**: Nodes with data and pointer to next; O(n) access, O(1) insert at head
- **Stack**: LIFO (Last In, First Out); push and pop operations
- **Queue**: FIFO (First In, First Out); enqueue and dequeue operations
- **Hash Table**: Key-value pairs; O(1) average lookup via hash function
- **Binary Tree**: Each node has at most two children; root, leaves, height
- **Binary Search Tree (BST)**: Left < parent < right; O(log n) search/insert if balanced
- **Heap**: Complete binary tree; max-heap (parent ≥ children) or min-heap
- **Graph**: Vertices and edges; directed/undirected, weighted/unweighted

### Algorithms
- **Sorting**: Bubble O(n²), Selection O(n²), Insertion O(n²), Merge O(n log n), Quick O(n log n) avg, Heap O(n log n)
- **Searching**: Linear O(n), Binary O(log n) (requires sorted)
- **Graph Traversal**: BFS (queue, level-order), DFS (stack/recursion, depth-first)
- **Shortest Path**: Dijkstra (non-negative weights), Bellman-Ford (negative weights), Floyd-Warshall (all pairs)
- **Minimum Spanning Tree**: Kruskal (edge-based, union-find), Prim (vertex-based, priority queue)
- **Dynamic Programming**: Optimal substructure + overlapping subproblems; memoization or tabulation
- **Greedy Algorithm**: Locally optimal choices; works when greedy choice property holds
- **Divide and Conquer**: Split problem, solve recursively, combine results

### Complexity
- **Big O Notation**: Asymptotic upper bound; O(1) < O(log n) < O(n) < O(n log n) < O(n²) < O(2ⁿ)
- **Time Complexity**: Operations as function of input size
- **Space Complexity**: Memory usage as function of input size
- **P vs NP**: P = solvable in polynomial time; NP = verifiable in polynomial time; P = NP is open question
- **NP-Complete**: Hardest problems in NP; reducible to each other

### Operating Systems
- **Process**: Running program instance; has memory space, state, and resources
- **Thread**: Lightweight process; shares memory with parent process
- **Concurrency**: Multiple tasks making progress; not necessarily simultaneous
- **Parallelism**: Truly simultaneous execution on multiple cores/processors
- **Deadlock**: Circular wait for resources; four conditions: mutual exclusion, hold-and-wait, no preemption, circular wait
- **Virtual Memory**: Abstraction over physical memory; paging and page tables
- **File System**: Organization of data on storage; directories, files, metadata

### Networking
- **OSI Model**: 7 layers — Physical, Data Link, Network, Transport, Session, Presentation, Application
- **TCP/IP**: Reliable, connection-oriented transport protocol; 3-way handshake
- **UDP**: Unreliable, connectionless; faster, used for streaming
- **HTTP/HTTPS**: Application layer protocol for web; HTTPS adds TLS encryption
- **DNS**: Domain Name System; translates domain names to IP addresses
- **IP Address**: Network identifier; IPv4 (32-bit) and IPv6 (128-bit)
- **Routing**: Forwarding packets between networks; routing tables, protocols (OSPF, BGP)

### Databases
- **Relational Database**: Tables with rows and columns; SQL; ACID properties
- **Primary Key**: Unique identifier for each row; no nulls
- **Foreign Key**: Reference to primary key in another table; maintains referential integrity
- **SQL**: Structured Query Language; SELECT, INSERT, UPDATE, DELETE, JOIN
- **Normalization**: Reducing redundancy; 1NF, 2NF, 3NF, BCNF
- **Index**: Data structure for fast lookup; B-tree, hash index
- **NoSQL**: Non-relational; document (MongoDB), key-value (Redis), column-family (Cassandra), graph (Neo4j)
- **Transaction**: Unit of work; ACID — Atomicity, Consistency, Isolation, Durability

### Programming Paradigms
- **Object-Oriented**: Classes, objects, inheritance, polymorphism, encapsulation
- **Functional**: Pure functions, immutability, higher-order functions, no side effects
- **Imperative**: Sequence of commands changing state
- **Declarative**: Describe what to compute, not how (SQL, HTML)
- **Recursion**: Function calling itself; base case + recursive case
