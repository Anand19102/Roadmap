# 🟩 ITSRUNTYM — 25 DSA PATTERNS

> **Role:** Pattern-recognition layer
> **Status:** 🟢 CORE SUPPLEMENTARY RESOURCE
> **Purpose:** Learn to recognize *which technique a problem is asking for.*

---

# 1. OFFICIAL RESOURCE

[ItsRunTym — Structured Interview Preparation Platform](https://itsruntym.com/?utm_source=chatgpt.com)

The platform currently describes its 25-pattern material as pattern-first DSA preparation and emphasizes structured problem solving over random LeetCode grinding.

---

# 2. THE CENTRAL PURPOSE

Kunal teaches:

> **How the algorithm/data structure works.**

ItsRunTym teaches:

> **How to recognize the pattern.**

NeetCode provides:

> **The interview problem environment where that recognition must work.**

Therefore:

```text
              KUNAL
       Concept + Implementation
                 ↓
            ITSRUNTYM
        Pattern Recognition
                 ↓
             NEETCODE
        Interview Application
```

---

# 3. OUR 25-PATTERN RESOURCE MAP

The user-supplied playlist breakdown is the authoritative syllabus for our roadmap.

---

## L1 — TWO POINTERS

### Classification

🔴 MASTER

### Learn

* opposite-direction pointers
* same-direction pointers
* pointer movement logic
* eliminating O(N²) brute force where appropriate

### Must understand

> Why moving one pointer is safe.

### Must practice

* Two Sum II
* 3Sum
* Container With Most Water
* related array/string pointer problems

---

# L2 — FAST AND SLOW POINTERS

### Classification

🔴 MASTER

### Learn

* Floyd's algorithm
* cycle detection
* middle node
* cycle entry

### Master

The reasoning behind pointer speed differences.

---

# L3 — SLIDING WINDOW

### Classification

🔴 MASTER

### Learn

* fixed window
* variable window
* expand
* shrink
* frequency tracking
* maintaining window invariants

### Must practice

Representative substring/subarray problems.

---

# L4 — PREFIX SUM

### Classification

🔴 MASTER

### Learn

* prefix preprocessing
* range sums
* cumulative information
* subarray reasoning

### Connect with

* HashMap
* subarray sum problems
* 2D prefix sums later if required

---

# L5 — MERGE INTERVALS

### Classification

🔴 MASTER

### Learn

* sorting intervals
* overlap detection
* merging
* scheduling interpretation

---

# L6 — BINARY SEARCH

### Classification

🔴 MASTER

### Learn

* sorted-array binary search
* boundary search
* monotonic search spaces
* answer-space binary search

### Critical

Do not learn binary search as one memorized loop.

Learn:

> **What property makes binary search valid?**

---

# L7 — SORTING ALGORITHMS

### Classification

🟠 STRONG UNDERSTANDING

### Learn

* Bubble Sort
* Selection Sort
* Insertion Sort
* Merge Sort
* Quick Sort

### Master

* complexity
* stability concept
* when sorting helps another algorithm

### Do not overinvest

You do not need to become a sorting-algorithm historian.

---

# L8 — HASHMAPS / INTERNAL WORKING

### Classification

🔴 MASTER PRACTICAL
🟠 STRONG INTERNAL UNDERSTANDING

### Learn

* hashing
* buckets
* collisions
* key/value lookup
* Java HashMap usage

### Important

Know enough internal implementation to answer interviews.

Do not spend disproportionate time rebuilding Java's HashMap internally.

---

# L9 — STACKS / STACK APPLICATIONS

### Classification

🔴 MASTER

### Learn

* LIFO
* parentheses
* monotonic stack
* next greater element

---

# L10 — QUEUES

### Classification

🔴 MASTER

### Learn

* FIFO
* queue variants
* BFS relationship
* implementation

---

# L11 + L13 — HEAP / PRIORITY QUEUE / TOP K

### Classification

🔴 MASTER

The creator combines these into one video in the supplied playlist structure.

### Learn

* min heap
* max heap
* PriorityQueue
* top K
* heap-based optimization

### Connect directly with

* K-way merge
* graph algorithms
* scheduling
* streaming problems

---

# L12 — K-WAY MERGE

### Classification

🟠 STRONG UNDERSTANDING

### Learn

* merging multiple sorted sources
* priority queue
* complexity reasoning

---

# L14 — TREES / TRAVERSALS

### Classification

🔴 MASTER

### Master

* tree terminology
* recursive traversal
* inorder
* preorder
* postorder

---

# L15 — DFS

### Classification

🔴 MASTER

### Learn

* recursion
* depth-first traversal
* backtracking relationship
* path problems

---

# L16 — BFS

### Classification

🔴 MASTER

### Learn

* queue
* level-order traversal
* shortest path in unweighted contexts
* level views

---

# L17 — GRAPHS / REPRESENTATION

### Classification

🔴 MASTER

### Master

* vertices
* edges
* adjacency list
* adjacency matrix
* directed/undirected graphs
* weighted/unweighted graphs

---

# L18 — DIJKSTRA

### Classification

🟠 STRONG UNDERSTANDING

### Master

* shortest path idea
* priority queue
* relaxation
* non-negative edge requirement

---

# L19 — TOPOLOGICAL SORT / KAHN

### Classification

🔴 MASTER

### Learn

* DAG
* indegree
* queue
* topological ordering
* cycle detection

---

# L20 — TRIE

### Classification

🟠 STRONG UNDERSTANDING

### Learn

* prefix tree
* character-by-character traversal
* prefix queries
* autocomplete-style applications

---

# L21 — GREEDY

### Classification

🔴 MASTER

### Learn

* local optimal choice
* proof/reasoning
* Jump Game
* Gas Station

### Critical

Do not memorize:

> “This problem is greedy.”

Instead ask:

> **Why is the greedy choice safe?**

---

# L22 — DYNAMIC PROGRAMMING

### Classification

🔴 MASTER

### Learn deeply

```text
Recursion
   ↓
Memoization
   ↓
Tabulation
   ↓
Space optimization
```

### Master

* state
* recurrence
* base case
* transition
* overlapping subproblems
* optimal substructure

---

# L23 — MINIMUM PATH SUM

### Classification

🔴 MASTER

### Purpose

Introduce 2D DP/grid-state reasoning.

Connect to:

* grid traversal
* state transitions
* path optimization

---

# L24 — BACKTRACKING

### Classification

🔴 MASTER

### Learn

* choose
* explore
* undo
* recursion tree
* subsets
* combinations
* permutations
* constraint search

---

# L25 — BITWISE OPERATIONS

### Classification

🟠 STRONG UNDERSTANDING

### Learn

* AND
* OR
* XOR
* shifts
* set bits
* unique number patterns

### Master practical interview patterns.

Do not turn this into an advanced bit-manipulation specialization unless required.

---

# 4. ORDERING RULE

The playlist's published order does **not automatically determine our study order**.

The Master Roadmap may reorder topics to respect prerequisites.

For example:

```text
Arrays
 ↓
Hashing
 ↓
Two Pointers
 ↓
Sliding Window
 ↓
Stack
 ↓
Binary Search
 ↓
Linked List
 ↓
Trees
 ↓
Heap
 ↓
Graphs
 ↓
Greedy
 ↓
DP
 ↓
Backtracking
```

The actual execution order will be determined by the integrated Kunal + NeetCode + ItsRunTym dependency graph.

---

# 5. PROBLEM-SOLVING RULE

After each pattern:

### Phase A — Recognition

Identify:

* input structure
* constraints
* required output
* repeated information
* monotonicity
* ordering
* state
* possible data structures

### Phase B — Brute force

Explain the naive approach.

### Phase C — Pattern identification

Explain:

> Why does this pattern fit?

### Phase D — Optimization

Derive the improved approach.

### Phase E — Code

Implement in Java.

### Phase F — Dry run

Use a non-trivial example.

### Phase G — Complexity

State:

* time
* space

### Phase H — Variation

Modify one constraint and reconsider the solution.

---

# 6. WHAT TO MEMORIZE

Memorize:

* pattern triggers
* invariants
* common templates
* pointer movement rules
* common complexity
* common edge cases

Do NOT memorize:

* entire problem solutions
* exact code
* problem-specific variable names

---

# 7. ITS RUNTYM'S SUCCESS CRITERION

A pattern is considered learned when you can look at a new problem and say:

> “This resembles ___ because ___.”

and then construct the solution without requiring the video.

---

# 8. RELATIONSHIP WITH NEETCODE

ItsRunTym comes **before or alongside** selected NeetCode problems.

Example:

```text
Sliding Window
      ↓
ItsRunTym lesson
      ↓
Understand invariant
      ↓
Solve selected NeetCode problems
      ↓
Record mistakes
      ↓
Reattempt later
```

---

# 9. FINAL RULE

ItsRunTym is **not another course to finish for the sake of completion**.

It exists to build:

> **Pattern recognition + transfer ability.**

The objective is not:

> “I watched all 25 videos.”

The objective is:

> “I can recognize the pattern in an unfamiliar interview problem.”
