# Computer Science Equations & Formulas

## ⏱️ Complexity Analysis

### Big-O Common Classes
- $O(1)$ — Constant: hash table lookup
- $O(\log n)$ — Logarithmic: binary search
- $O(n)$ — Linear: linear search, single loop
- $O(n \log n)$ — Linearithmic: merge sort, heap sort
- $O(n^2)$ — Quadratic: bubble sort, nested loops
- $O(n^3)$ — Cubic: naive matrix multiplication
- $O(2^n)$ — Exponential: brute-force subsets
- $O(n!)$ — Factorial: brute-force permutations

### Master Theorem
For recurrences $T(n) = aT(n/b) + O(n^d)$:
- If $d < \log_b a$: $T(n) = O(n^{\log_b a})$
- If $d = \log_b a$: $T(n) = O(n^d \log n)$
- If $d > \log_b a$: $T(n) = O(n^d)$

### Amortized Analysis
- **Aggregate**: Total cost / number of operations
- **Accounting**: Assign amortized cost; bank surplus for expensive ops
- **Potential**: $\hat{c}_i = c_i + \Phi(D_i) - \Phi(D_{i-1})$

## 🔢 Sorting Algorithm Complexities

| Algorithm | Best | Average | Worst | Space | Stable |
|-----------|------|---------|-------|-------|--------|
| Bubble | $O(n)$ | $O(n^2)$ | $O(n^2)$ | $O(1)$ | Yes |
| Selection | $O(n^2)$ | $O(n^2)$ | $O(n^2)$ | $O(1)$ | No |
| Insertion | $O(n)$ | $O(n^2)$ | $O(n^2)$ | $O(1)$ | Yes |
| Merge | $O(n\log n)$ | $O(n\log n)$ | $O(n\log n)$ | $O(n)$ | Yes |
| Quick | $O(n\log n)$ | $O(n\log n)$ | $O(n^2)$ | $O(\log n)$ | No |
| Heap | $O(n\log n)$ | $O(n\log n)$ | $O(n\log n)$ | $O(1)$ | No |
| Counting | $O(n+k)$ | $O(n+k)$ | $O(n+k)$ | $O(k)$ | Yes |
| Radix | $O(nk)$ | $O(nk)$ | $O(nk)$ | $O(n+k)$ | Yes |

## 🌳 Data Structure Complexities

| Structure | Search | Insert | Delete | Space |
|-----------|--------|--------|--------|-------|
| Array | $O(n)$ | $O(n)$ | $O(n)$ | $O(n)$ |
| Sorted Array | $O(\log n)$ | $O(n)$ | $O(n)$ | $O(n)$ |
| Linked List | $O(n)$ | $O(1)$ | $O(1)$ | $O(n)$ |
| Hash Table | $O(1)$ avg | $O(1)$ avg | $O(1)$ avg | $O(n)$ |
| BST (balanced) | $O(\log n)$ | $O(\log n)$ | $O(\log n)$ | $O(n)$ |
| Heap | $O(n)$ | $O(\log n)$ | $O(\log n)$ | $O(n)$ |
| B-Tree | $O(\log n)$ | $O(\log n)$ | $O(\log n)$ | $O(n)$ |

## 📊 Graph Algorithms

### Shortest Path
- **Dijkstra**: $O((V + E) \log V)$ with min-heap; non-negative weights
- **Bellman-Ford**: $O(VE)$; handles negative weights; detects negative cycles
- **Floyd-Warshall**: $O(V^3)$; all-pairs shortest paths
  - $d[i][j] = \min(d[i][j],\ d[i][k] + d[k][j])$

### Minimum Spanning Tree
- **Kruskal**: $O(E \log E)$; sort edges, union-find
- **Prim**: $O((V + E) \log V)$ with min-heap

### Graph Properties
- Tree: $|E| = |V| - 1$ (connected, acyclic)
- Euler circuit exists iff all degrees even (connected graph)
- Planar graph: $|E| \leq 3|V| - 6$ (Euler's formula: $V - E + F = 2$)
- Chromatic number: $\chi(G) \leq \Delta(G) + 1$ (Brooks' theorem)
- Handshaking lemma: $\sum_{v} \deg(v) = 2|E|$

## 🔐 Information Theory

- **Entropy**: $H(X) = -\sum_{i} p_i \log_2 p_i$ (bits)
- **Mutual Information**: $I(X;Y) = H(X) - H(X|Y) = H(Y) - H(Y|X)$
- **Shannon's Source Coding**: Average code length $\geq H(X)$
- **Channel Capacity**: $C = \max_{p(x)} I(X;Y)$

## 🔑 Cryptography

### RSA
- Choose primes $p, q$; $n = pq$; $\phi(n) = (p-1)(q-1)$
- Public key: $(e, n)$ where $\gcd(e, \phi(n)) = 1$
- Private key: $d \equiv e^{-1} \pmod{\phi(n)}$
- Encrypt: $c = m^e \mod n$
- Decrypt: $m = c^d \mod n$

### Hashing
- **Hash function**: $h: U \rightarrow \{0, 1, ..., m-1\}$
- **Load factor**: $\alpha = n/m$ (entries / table size)
- **Birthday paradox**: Collision expected after $\sim\sqrt{\pi m/2}$ insertions

## 🔄 Recurrence Relations

- **Linear search**: $T(n) = T(n-1) + O(1) \Rightarrow O(n)$
- **Binary search**: $T(n) = T(n/2) + O(1) \Rightarrow O(\log n)$
- **Merge sort**: $T(n) = 2T(n/2) + O(n) \Rightarrow O(n\log n)$
- **Fibonacci**: $F(n) = F(n-1) + F(n-2)$; naive $O(2^n)$; DP $O(n)$; matrix $O(\log n)$
- **Towers of Hanoi**: $T(n) = 2T(n-1) + 1 = 2^n - 1$

## 📐 Computational Geometry

- **Convex hull**: Graham scan $O(n\log n)$; Jarvis march $O(nh)$
- **Closest pair**: Divide and conquer $O(n\log n)$
- **Line intersection**: Sweep line $O((n+k)\log n)$ where $k$ = intersections

## 🧮 Number Theory (CS Applications)

- **Modular exponentiation**: $a^b \mod m$ in $O(\log b)$ using repeated squaring
- **GCD**: Euclidean algorithm $O(\log(\min(a,b)))$
- **Extended Euclidean**: $ax + by = \gcd(a,b)$
- **Fermat's little theorem**: $a^{p-1} \equiv 1 \pmod{p}$ (p prime, $\gcd(a,p)=1$)
- **Chinese Remainder Theorem**: System $x \equiv a_i \pmod{m_i}$ has unique solution mod $\prod m_i$
