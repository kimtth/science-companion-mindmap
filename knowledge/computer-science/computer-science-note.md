# Computer Science - Comprehensive Notes

## 📋 Table of Contents
1. [Data Structures](#1-data-structures)
2. [Algorithms](#2-algorithms)
3. [Operating Systems](#3-operating-systems)
4. [Networking](#4-networking)
5. [Databases](#5-databases)
6. [Programming Languages](#6-programming-languages)
7. [Software Engineering](#7-software-engineering)
8. [Theory of Computation](#8-theory-of-computation)

---

## 📚 Main Topics

### 1. Data Structures
Organizing and storing data for efficient access and modification.

- **Arrays**: Contiguous memory; O(1) random access; fixed or dynamic size
  - Static arrays: fixed size at allocation
  - Dynamic arrays (ArrayList, vector): amortized O(1) append, doubles capacity
- **Linked Lists**: Nodes with data + pointer; O(1) insert/delete at known position
  - Singly linked: forward traversal only
  - Doubly linked: bidirectional traversal; O(1) delete with node reference
  - Circular: last node points to first
- **Stacks**: LIFO; push/pop O(1); used in function calls, undo, expression parsing
- **Queues**: FIFO; enqueue/dequeue O(1); used in BFS, scheduling
  - Priority queue: dequeue by priority; heap-backed O(log n)
  - Deque: double-ended; insert/remove both ends
- **Hash Tables**: Key-value mapping; O(1) average lookup/insert/delete
  - Hash function maps key → index; load factor α = n/m
  - Collision resolution: chaining (linked lists), open addressing (linear/quadratic probing)
  - Worst case O(n) if many collisions; resize when α exceeds threshold
- **Trees**:
  - **Binary Tree**: Each node ≤ 2 children; height h; n nodes → h ≥ log₂(n)
  - **BST**: Left < parent < right; O(h) search/insert/delete; degenerate → O(n)
  - **Balanced BSTs**: AVL (balance factor ≤ 1), Red-Black (color properties), guaranteeing O(log n)
  - **B-Tree**: Multi-way balanced; used in databases/filesystems; all leaves same depth
  - **Trie**: Prefix tree; string lookup O(key length); used in autocomplete, dictionaries
  - **Heap**: Complete binary tree; max-heap parent ≥ children; priority queue backbone
    - Insert O(log n), extract-max O(log n), build-heap O(n)
- **Graphs**: Vertices + edges; directed/undirected; weighted/unweighted
  - Adjacency matrix: O(V²) space, O(1) edge lookup
  - Adjacency list: O(V+E) space, O(degree) edge lookup
  - Dense graph: E ≈ V²; sparse: E ≈ V

### 2. Algorithms
Systematic procedures for solving computational problems.

**Sorting Algorithms**:
- **Comparison-based** (lower bound Ω(n log n)):
  - Bubble sort: O(n²); swap adjacent; adaptive (O(n) if sorted)
  - Selection sort: O(n²); find min, place at front; not stable
  - Insertion sort: O(n²); insert each element in sorted portion; good for small/nearly sorted
  - Merge sort: O(n log n); divide-and-conquer; stable; O(n) extra space
  - Quick sort: O(n log n) average, O(n²) worst; in-place; pivot selection matters
  - Heap sort: O(n log n); in-place; not stable
- **Non-comparison** (can beat n log n):
  - Counting sort: O(n+k) for range k; stable
  - Radix sort: O(d(n+k)) for d digits; stable
  - Bucket sort: O(n) average for uniform distribution

**Searching Algorithms**:
- Linear search: O(n); unsorted data
- Binary search: O(log n); requires sorted; divide search space by half
- Interpolation search: O(log log n) average for uniform distribution
- Hash-based: O(1) average via hash table

**Graph Algorithms**:
- **BFS** (Breadth-First): Queue-based; O(V+E); shortest path in unweighted graphs; level-order
- **DFS** (Depth-First): Stack/recursion; O(V+E); topological sort, cycle detection, connected components
- **Dijkstra**: Shortest path from source; O((V+E) log V) with min-heap; non-negative weights only
- **Bellman-Ford**: O(VE); handles negative weights; detects negative cycles
- **Floyd-Warshall**: O(V³); all-pairs shortest paths; DP on intermediate vertices
- **Kruskal's MST**: Sort edges, union-find; O(E log E)
- **Prim's MST**: Grow from vertex; O((V+E) log V) with min-heap
- **Topological Sort**: DAG only; DFS-based or Kahn's (in-degree); O(V+E)

**Dynamic Programming**:
- Optimal substructure + overlapping subproblems
- Top-down (memoization) vs bottom-up (tabulation)
- Classic problems: Fibonacci, knapsack, longest common subsequence, edit distance, coin change
- Time-space tradeoff: store computed results to avoid recomputation

**Greedy Algorithms**:
- Make locally optimal choice at each step
- Works when greedy choice property + optimal substructure hold
- Examples: Huffman coding, activity selection, fractional knapsack, Dijkstra

**Divide and Conquer**:
- Split into subproblems, solve recursively, combine
- Master theorem: T(n) = aT(n/b) + O(nᵈ)
- Examples: merge sort, quick sort, closest pair, Strassen matrix multiplication

### 3. Operating Systems
System software managing hardware resources and providing services.

- **Process Management**:
  - Process: running program instance with own address space
  - Thread: lightweight; shares memory within process
  - Context switch: save/restore state; expensive (cache invalidation)
  - Process states: new → ready → running → waiting → terminated
  - Scheduling: FCFS, SJF, Round Robin, Priority, Multilevel Queue
    - Preemptive vs non-preemptive
    - Metrics: turnaround time, waiting time, response time, throughput
- **Memory Management**:
  - Virtual memory: abstraction; each process sees continuous address space
  - Paging: fixed-size pages; page table maps virtual → physical
  - Page replacement: FIFO, LRU, Optimal (Bélády)
  - Segmentation: variable-size logical segments
  - TLB: Translation Lookaside Buffer; cache for page table entries
  - Thrashing: excessive paging; working set too large for physical memory
- **Concurrency & Synchronization**:
  - Race condition: outcome depends on timing of threads
  - Critical section: code accessing shared resource; must be mutually exclusive
  - Mutex: binary lock; one thread at a time
  - Semaphore: counting lock; permits N concurrent accesses
  - Deadlock conditions (all four required): mutual exclusion, hold-and-wait, no preemption, circular wait
  - Deadlock handling: prevention, avoidance (Banker's algorithm), detection, recovery
- **File Systems**:
  - Hierarchy: directories, files, metadata (permissions, timestamps)
  - Allocation: contiguous, linked, indexed (inode)
  - Journaling: write intentions before data; crash recovery
  - Examples: ext4, NTFS, APFS, ZFS

### 4. Networking
Communication between computers across interconnected networks.

- **OSI Model** (7 layers):
  1. Physical: bits over medium (copper, fiber, wireless)
  2. Data Link: frames; MAC addressing; Ethernet, WiFi; error detection (CRC)
  3. Network: packets; IP addressing; routing (OSPF, BGP)
  4. Transport: segments; TCP (reliable, ordered, connection-oriented) / UDP (fast, connectionless)
  5. Session: dialog control; establishing/maintaining connections
  6. Presentation: data format, encryption, compression
  7. Application: HTTP, FTP, SMTP, DNS, SSH
- **TCP/IP**:
  - 3-way handshake: SYN → SYN-ACK → ACK
  - Flow control: sliding window
  - Congestion control: slow start, congestion avoidance, fast retransmit
  - Reliable delivery: sequence numbers, ACKs, retransmission
- **HTTP/HTTPS**:
  - Request methods: GET, POST, PUT, DELETE, PATCH
  - Status codes: 2xx success, 3xx redirect, 4xx client error, 5xx server error
  - HTTPS: HTTP + TLS encryption; certificates, public key infrastructure
- **DNS**: Hierarchical naming; root → TLD → authoritative; recursive/iterative queries; caching
- **Security**: Firewalls, VPN, TLS/SSL, symmetric (AES) vs asymmetric (RSA) encryption

### 5. Databases
Organized storage, retrieval, and management of structured data.

- **Relational Model**: Tables (relations) with rows (tuples) and columns (attributes)
  - Primary key: unique identifier; foreign key: reference to another table
  - SQL: DDL (CREATE, ALTER, DROP), DML (SELECT, INSERT, UPDATE, DELETE)
  - JOINs: INNER, LEFT, RIGHT, FULL OUTER, CROSS
- **Normalization**: Eliminate redundancy
  - 1NF: atomic values, no repeating groups
  - 2NF: 1NF + no partial dependencies (on part of composite key)
  - 3NF: 2NF + no transitive dependencies
  - BCNF: every determinant is a candidate key
- **ACID Properties**: Atomicity, Consistency, Isolation, Durability
- **Indexing**: B-tree (range queries), hash index (equality), bitmap index
- **Transactions**: BEGIN, COMMIT, ROLLBACK; isolation levels (read uncommitted → serializable)
- **NoSQL**: Document (MongoDB), key-value (Redis), column-family (Cassandra), graph (Neo4j)
  - CAP theorem: Consistency, Availability, Partition tolerance — pick 2
  - BASE: Basically Available, Soft state, Eventually consistent

### 6. Programming Languages
Formal languages for expressing computation.

- **Paradigms**: Imperative, Object-Oriented, Functional, Declarative, Logic
- **Type Systems**: Static vs dynamic; strong vs weak; type inference
- **Compilation**: Source → lexer → parser → AST → semantic analysis → code generation → machine code
  - Compiler: ahead-of-time (C, Go, Rust)
  - Interpreter: line-by-line (Python, Ruby)
  - JIT: compile at runtime (Java JVM, .NET CLR, JavaScript V8)
- **Memory Management**: Manual (C malloc/free), garbage collection (Java, Go, Python)
  - Reference counting, mark-and-sweep, generational GC
- **Concurrency Models**: Threads (shared memory), actors (message passing), async/await, CSP (Go channels)

### 7. Software Engineering
Disciplined approach to developing reliable software systems.

- **Development Methodologies**: Waterfall, Agile (Scrum, Kanban), XP, DevOps
- **Design Patterns** (Gang of Four):
  - Creational: Singleton, Factory, Builder, Prototype
  - Structural: Adapter, Decorator, Proxy, Facade, Composite
  - Behavioral: Observer, Strategy, Command, Iterator, State
- **SOLID Principles**:
  - Single Responsibility: one reason to change
  - Open/Closed: open for extension, closed for modification
  - Liskov Substitution: subtypes replaceable for base types
  - Interface Segregation: many specific interfaces > one general
  - Dependency Inversion: depend on abstractions, not concretions
- **Testing**: Unit, integration, system, acceptance; TDD; coverage metrics
- **Version Control**: Git; branching strategies (feature branches, GitFlow, trunk-based)
- **CI/CD**: Continuous Integration (build/test on merge), Continuous Deployment (auto-deploy)

### 8. Theory of Computation
Mathematical foundations of what can and cannot be computed.

- **Automata Theory**:
  - Finite automata (DFA/NFA): regular languages; regex
  - Pushdown automata (PDA): context-free languages; CFG
  - Turing machine: recursively enumerable languages; universal computation
- **Chomsky Hierarchy**: Regular ⊂ Context-Free ⊂ Context-Sensitive ⊂ Recursively Enumerable
- **Computability**:
  - Decidable: algorithm always halts with correct answer
  - Undecidable: no algorithm exists (Halting Problem, Post Correspondence)
  - Church-Turing thesis: Turing machine captures all "effectively computable" functions
- **Complexity Classes**:
  - P: solvable in polynomial time
  - NP: verifiable in polynomial time
  - NP-Complete: hardest in NP; all NP reducible to these (SAT, 3-SAT, Clique, Vertex Cover)
  - NP-Hard: at least as hard as NP-Complete; may not be in NP
  - P = NP? Open millennium problem
  - PSPACE, EXPTIME, BPP, RP: other important classes

---

## 🔗 Interconnections
- Data structures underpin all algorithms
- OS concepts (concurrency, memory) affect system design
- Databases use trees (B-tree) and hashing extensively
- Networking protocols implement state machines (automata theory)
- Complexity theory guides algorithm design choices
