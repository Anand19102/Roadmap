# 🧠 DSA SEQUENCE

## Java DSA → Pattern Recognition → NeetCode 150 → Interview Readiness

> **Master-roadmap file**
>
> This file defines the permanent DSA architecture of the MEC Career Roadmap.
>
> It does **not** prescribe exact daily dates. Daily and weekly execution belongs in `01_CURRENT_EXECUTION/`.
>
> **Primary DSA language:** Java
> **Primary conceptual sources:** Kunal Kushwaha + Java foundation from Telusko
> **Pattern-recognition layer:** ItsRunTym
> **Problem/practice layer:** NeetCode 150 + LeetCode
> **Goal:** Become capable of recognizing, explaining, implementing and solving interview problems—not merely completing playlists.

---

# 1. DSA END GOAL

The objective is not:

> "Finish a DSA course."

The objective is:

> **Given an unfamiliar coding problem, identify the relevant data structure/algorithmic pattern, derive an approach, implement it cleanly in Java, analyse complexity, test edge cases, and explain the solution.**

By the placement-preparation stage, the target capability is:

```text
Problem
   ↓
Understand constraints
   ↓
Identify brute force
   ↓
Recognize pattern
   ↓
Choose data structure
   ↓
Derive optimized approach
   ↓
Implement in Java
   ↓
Test edge cases
   ↓
Analyse time + space
   ↓
Explain solution
   ↓
Recognize variations
```

---

# 2. THE THREE-LAYER DSA ARCHITECTURE

We deliberately do **not** study Kunal, ItsRunTym and NeetCode as three independent courses.

Instead:

```text
TELUSKO / JAVA FOUNDATION
        ↓
Java syntax + Collections + OOP
        ↓
KUNAL KUSHWAHA
Conceptual DSA foundation
        ↓
ITSRUNTYM
Pattern recognition
        ↓
NEETCODE 150
Curated interview problem practice
        ↓
LEETCODE
Independent problem solving
```

### Roles

| Source             | Role                                                           |
| ------------------ | -------------------------------------------------------------- |
| **Telusko**        | Java language + Collections foundation                         |
| **Kunal Kushwaha** | DSA concepts, implementation and foundational problem solving  |
| **ItsRunTym**      | Pattern recognition and interview-oriented technique selection |
| **NeetCode 150**   | Structured problem set and repetition                          |
| **LeetCode**       | Independent solving and interview simulation                   |

---

# 3. DSA MASTERY STANDARD

The five-level system defined in `02_KEEP_IN_MIND/01_MASTERY_CLASSIFICATION_SYSTEM.md` applies throughout this file.

### 🔴 MASTER

You must be able to:

* explain the concept without notes
* implement it from scratch
* identify when to use it
* identify when **not** to use it
* analyse time complexity
* analyse space complexity
* solve standard interview problems
* solve reasonable variations
* debug your implementation
* explain your solution verbally

### 🟠 STRONG UNDERSTANDING

You should:

* understand the mechanism deeply
* implement the standard version
* recognize common applications
* solve representative problems
* understand complexity

But you do not need extreme mastery of every obscure variation.

### 🟡 LEARN / USE

You should:

* understand the purpose
* know the standard implementation/API
* use it correctly when prompted
* solve basic applications

Do not spend disproportionate time here.

### 🟢 SKIM

Understand:

* what it is
* why it exists
* where it appears

Then move on.

### ⚪ SKIP FOR NOW

Do not spend meaningful study time unless a future project/interview specifically requires it.

---

# 4. THE MASTER DSA ORDER

The roadmap follows this dependency order:

```text
1. Java Foundations
        ↓
2. Complexity Analysis
        ↓
3. Arrays + Strings
        ↓
4. Hashing
        ↓
5. Two Pointers
        ↓
6. Sliding Window
        ↓
7. Prefix Sum
        ↓
8. Linked Lists
        ↓
9. Fast & Slow Pointers
        ↓
10. Stack
        ↓
11. Queue
        ↓
12. Binary Search
        ↓
13. Sorting
        ↓
14. Trees + Traversals
        ↓
15. DFS
        ↓
16. BFS
        ↓
17. Heap / Priority Queue
        ↓
18. Top K
        ↓
19. K-way Merge
        ↓
20. Intervals
        ↓
21. Backtracking
        ↓
22. Trie
        ↓
23. Graph Representation
        ↓
24. Graph Traversal
        ↓
25. Dijkstra
        ↓
26. Topological Sort
        ↓
27. Greedy
        ↓
28. 1D DP
        ↓
29. 2D DP
        ↓
30. Bit Manipulation
        ↓
31. Advanced interview combinations
```

The exact ordering deliberately differs slightly from the numbered order of ItsRunTym because **prerequisites matter more than playlist numbering**.

---

# 5. PHASE 0 — JAVA FOUNDATION FOR DSA

## Prerequisite Java topics

Before serious DSA begins, establish competence in:

* variables
* data types
* type conversion
* operators
* conditionals
* loops
* methods
* arrays
* strings
* classes and objects
* basic OOP
* ArrayList
* Set
* Map
* Comparator / Comparable
* generics
* basic exception handling

Telusko's Core Java section explicitly covers variables, data types, operators, conditionals, loops, classes/objects, methods, arrays and strings.

Telusko subsequently covers ArrayList, Set, Map, Comparator/Comparable and Generics.

### Mastery

| Topic                | Level |
| -------------------- | ----: |
| Java syntax          |    🔴 |
| Variables/data types |    🔴 |
| Operators            |    🔴 |
| Conditions           |    🔴 |
| Loops                |    🔴 |
| Methods              |    🔴 |
| Arrays               |    🔴 |
| Strings              |    🔴 |
| ArrayList            |    🔴 |
| HashMap / Map        |    🔴 |
| HashSet / Set        |    🔴 |
| Comparator           |    🟠 |
| Comparable           |    🟠 |
| Generics             |    🟠 |
| Exceptions           |    🟡 |
| Multithreading       |    🟡 |

---

# 6. PHASE 1 — COMPLEXITY

## Topics

* Big-O
* time complexity
* space complexity
* best/average/worst case
* constant
* logarithmic
* linear
* linearithmic
* quadratic
* exponential
* nested loops
* recursion complexity
* auxiliary space

### Mastery

🔴 MASTER

### Must be able to do

Given code:

```java
for (...)
    for (...)
```

you should be able to derive its complexity rather than memorize an answer.

---

# 7. PHASE 2 — ARRAYS + HASHING

## Core concepts

* array traversal
* insertion/deletion implications
* frequency counting
* indexing
* in-place modification
* prefix/suffix concepts
* HashMap
* HashSet
* frequency maps
* lookup optimization

### Kunal

Use Kunal's arrays/data-structure foundation here.

### ItsRunTym

Do:

> **L4 — Prefix Sum**

at the point where prefix/suffix reasoning becomes useful.

### ItsRunTym L4 — Prefix Sum

**Classification:** 🟠 STRONG UNDERSTANDING

Understand:

* prefix array construction
* cumulative state
* range sum queries
* reducing repeated work
* when prefix sums help
* when they do not

### NeetCode

Begin the **Arrays & Hashing** section only after the Java Array + HashMap/HashSet foundation is operational.

### Mastery

🔴

---

# 8. PHASE 3 — TWO POINTERS

## ItsRunTym

### L1 — Two Pointers

**Classification:** 🔴 MASTER

Exact conceptual targets:

* opposite-end pointers
* same-direction pointers
* pointer movement logic
* brute force → linear optimization
* Two Sum variations

### Required recognition skill

You must learn to ask:

> "Can I represent the problem with two moving indices instead of repeatedly examining the same elements?"

### NeetCode

Then begin the relevant **Two Pointers** problems.

### Mastery

🔴

---

# 9. PHASE 4 — SLIDING WINDOW

## ItsRunTym

### L3 — Sliding Window

**Classification:** 🔴 MASTER

Learn:

* fixed-size window
* variable-size window
* expand right
* shrink left
* maintaining window state
* frequency maps
* validity conditions
* longest/shortest window patterns

### NeetCode

Move into relevant **Sliding Window** problems.

### Mastery

🔴

---

# 10. PHASE 5 — LINKED LISTS

## Topics

* node structure
* traversal
* insertion
* deletion
* singly linked list
* doubly linked list
* reversing
* pointer manipulation

### Mastery

🔴

---

# 11. PHASE 6 — FAST & SLOW POINTERS

## ItsRunTym

### L2 — Fast and Slow Pointers

**Classification:** 🔴 MASTER

Learn:

* Floyd's Tortoise and Hare
* cycle detection
* middle node
* cycle starting point
* pointer-speed reasoning
* Linked List applications

### Prerequisite

Two-pointer thinking + Linked Lists.

---

# 12. PHASE 7 — STACK

## ItsRunTym

### L9 — Stacks / Where Stack is Applied

**Classification:** 🔴 MASTER

Learn:

* LIFO
* stack implementation/use
* parentheses matching
* monotonic stack
* next greater element
* previous greater/smaller patterns

### Important

Monotonic stack is not merely a syntax topic.

You must recognize:

> "I need to maintain candidates while removing elements that can never become the answer."

---

# 13. PHASE 8 — QUEUE

## ItsRunTym

### L10 — Queue & Types

**Classification:** 🟠 STRONG UNDERSTANDING

Learn:

* FIFO
* queue operations
* types of queues
* implementation concepts
* relationship to BFS

Do not over-invest in obscure queue variants.

---

# 14. PHASE 9 — BINARY SEARCH

## ItsRunTym

### L6 — Binary Search

**Classification:** 🔴 MASTER

Learn:

* sorted-array binary search
* left/right boundaries
* midpoint
* search-space reduction
* first/last occurrence
* lower/upper-bound style reasoning
* binary search on monotonic answer spaces

### Critical skill

Do not restrict binary search to:

> "Find x in sorted array."

You must recognize:

> "Is the answer space monotonic?"

### NeetCode

Complete the relevant **Binary Search** problems after mastering implementation.

---

# 15. PHASE 10 — SORTING

## ItsRunTym

### L7 — All Sorting Algorithms

**Classification:** 🟠 STRONG UNDERSTANDING

Study:

* Bubble Sort
* Selection Sort
* Insertion Sort
* Merge Sort
* QuickSort

### What to memorize

Memorize:

* basic complexity
* stability where relevant
* broad characteristics
* when sorting is useful

### What to master

🔴:

* Merge Sort idea
* partitioning idea of QuickSort
* using sorting as a preprocessing step

### What not to do

Do not spend weeks manually implementing every sorting algorithm repeatedly.

---

# 16. PHASE 11 — TREES

## ItsRunTym

### L14 — Trees / Traversals

**Classification:** 🔴 MASTER

Learn:

* binary tree anatomy
* recursive traversal
* inorder
* preorder
* postorder

### L15 — DFS

**Classification:** 🔴 MASTER

Learn:

* recursion
* depth-first traversal
* tree depth
* path sums
* backtracking relationship

### L16 — BFS

**Classification:** 🔴 MASTER

Learn:

* queue-based traversal
* level-order traversal
* level processing
* left/right views
* level nodes

### Required order

```text
Tree basics
 ↓
Recursive traversal
 ↓
DFS
 ↓
BFS
 ↓
Tree problem patterns
```

---

# 17. PHASE 12 — HEAP / PRIORITY QUEUE

## ItsRunTym

### L11 + L13 — Heap + Top K Elements

**Classification:** 🔴 MASTER

Learn:

* min heap
* max heap
* PriorityQueue
* heap insertion/removal
* top K
* kth largest/smallest
* heap-based optimization

### L12 — K-way Merge

**Classification:** 🟠 STRONG UNDERSTANDING

Learn:

* merging K sorted arrays/lists
* priority queue as a frontier
* complexity reasoning

---

# 18. PHASE 13 — INTERVALS

## ItsRunTym

### L5 — Merge Intervals

**Classification:** 🔴 MASTER

Learn:

* sorting intervals
* overlap detection
* merging
* meeting/calendar problems
* interval ordering

---

# 19. PHASE 14 — BACKTRACKING

## ItsRunTym

### L24 — Backtracking

**Classification:** 🔴 MASTER

Learn:

* recursive exploration
* choose
* recurse
* undo
* subsets
* combinations
* constraint search
* Rat in a Maze-style reasoning

Core mental model:

```text
Choose
 ↓
Explore
 ↓
Undo
```

---

# 20. PHASE 15 — TRIE

## ItsRunTym

### L20 — Trie Data Structure

**Classification:** 🟠 STRONG UNDERSTANDING

Learn:

* prefix tree
* character-by-character insertion
* search
* prefix search
* autocomplete
* string matching

Master standard Trie implementation.

Do not spend disproportionate time on exotic Trie variants.

---

# 21. PHASE 16 — GRAPHS

## ItsRunTym

### L17 — Graphs & Representation

**Classification:** 🔴 MASTER**

Learn:

* vertices
* edges
* directed/undirected
* weighted/unweighted
* adjacency matrix
* adjacency list

### Required implementation skill

You must comfortably construct:

```text
List<List<Integer>>
```

style adjacency-list representations in Java.

---

# 22. GRAPH TRAVERSAL

### DFS

🔴 MASTER

### BFS

🔴 MASTER

Understand:

* visited arrays/sets
* connected components
* traversal
* cycle-related reasoning
* grid-as-graph thinking

---

# 23. DIJKSTRA

## ItsRunTym

### L18 — Dijkstra Algorithm

**Classification:** 🟠 STRONG UNDERSTANDING → 🔴 MASTER before serious graph interview preparation

Learn:

* weighted graphs
* shortest path
* PriorityQueue
* relaxation
* distance array
* stale priority-queue entries
* complexity

Do not merely memorize the code.

Understand **why relaxation works**.

---

# 24. TOPOLOGICAL SORT

## ItsRunTym

### L19 — Topological Sort / Kahn's Algorithm

**Classification:** 🔴 MASTER

Learn:

* DAG
* indegree
* Kahn's algorithm
* BFS interpretation
* cycle detection
* prerequisite/course scheduling

Also understand DFS-based conceptual topological ordering at least at 🟠 level.

---

# 25. GREEDY

## ItsRunTym

### L21 — Greedy Approach

**Classification:** 🔴 MASTER

Study:

* local optimal choice
* global consequence
* recognizing greedy structure
* Jump Game 1
* Jump Game 2
* Gas Station

### Critical distinction

Do not memorize:

> "This problem is greedy."

Instead learn:

> "Why is the local choice safe?"

---

# 26. DYNAMIC PROGRAMMING

## ItsRunTym

### L22 — Dynamic Programming

**Classification:** 🔴 MASTER

Learn:

```text
Recursion
 ↓
Memoization
 ↓
Tabulation
```

using the House Robber foundation.

You must understand:

* overlapping subproblems
* state
* recurrence
* base case
* transition
* memoization
* tabulation
* space optimization

---

# 27. 1D DP

After the basic DP model:

* House Robber
* climbing/stair-style problems
* subsequence/state problems
* take/not-take patterns
* partition/state transitions

### Mastery

🔴

---

# 28. 2D DP

## ItsRunTym

### L23 — Minimum Path Sum

**Classification:** 🔴 MASTER

Learn:

* grid state
* transition
* boundary handling
* minimum-cost path
* 2D tabulation

Then expand into broader NeetCode 2-D DP problems.

---

# 29. BIT MANIPULATION

## ItsRunTym

### L25 — Bitwise Operations

**Classification:** 🟠 STRONG UNDERSTANDING

Learn:

* AND
* OR
* XOR
* left shift
* right shift
* set bits
* unique-number problems
* bit counting
* masks

### Must know

Common XOR properties should be memorized.

Do not over-invest in obscure bit tricks unless placement practice demonstrates repeated need.

---

# 30. NEETCODE 150 INTEGRATION

NeetCode is **not a separate course**.

The sequence is:

```text
Concept learned
      ↓
Kunal foundational practice
      ↓
ItsRunTym pattern lesson
      ↓
NeetCode problems
      ↓
LeetCode independent problems
      ↓
Revision
```

The major NeetCode categories are integrated according to prerequisites:

1. Arrays & Hashing
2. Two Pointers
3. Sliding Window
4. Stack
5. Binary Search
6. Linked List
7. Trees
8. Tries
9. Heap / Priority Queue
10. Backtracking
11. Graphs
12. Advanced Graphs
13. 1-D Dynamic Programming
14. 2-D Dynamic Programming
15. Greedy
16. Intervals
17. Math & Geometry
18. Bit Manipulation

---

# 31. DSA INTERNSHIP TARGET

Before the main internship-preparation window, the target is:

### 🔴 Core interview readiness

* Arrays
* Hashing
* Strings
* Two Pointers
* Sliding Window
* Stack
* Binary Search
* Linked Lists
* Trees
* BFS/DFS
* Heap/Priority Queue
* basic Graphs
* Greedy
* basic DP
* Intervals

### 🟠 Strong extension

* Tries
* Dijkstra
* Topological Sort
* Backtracking
* 2D DP
* Bit Manipulation
* K-way Merge

---

# 32. PLACEMENT-END TARGET

By the main placement-preparation stage:

```text
NeetCode 150
        +
LeetCode independent practice
        +
Pattern recognition
        +
Timed solving
        +
Mixed-topic practice
        +
Mock interviews
```

The objective is **not necessarily 150/150 completed mechanically**.

The objective is:

> High-quality mastery of the important patterns represented by the set.

---

# 33. DSA REVISION ARCHITECTURE

Every major topic gets:

### R1 — immediate

Same day / next session.

### R2 — short interval

Within approximately one week.

### R3 — medium interval

Approximately 2–4 weeks later.

### R4 — long interval

Approximately 1–2 months later.

### R5 — interview revision

During internship/placement preparation.

Revision should include:

* concept recall
* template recall
* one representative problem
* one variation
* complexity recall
* common mistakes

---

# 34. DSA COMPLETION STANDARD

A topic is **not complete** merely because:

* the video is finished
* notes are written
* code was copied
* one problem was solved

A topic becomes complete when you can:

> **Recognize → Explain → Implement → Solve → Vary → Analyse → Recall**

---

# 35. FINAL DSA PRIORITY

```text
🔴 MASTER
Arrays / Hashing
Two Pointers
Sliding Window
Linked Lists
Stack
Binary Search
Trees
DFS
BFS
Heap
Graphs
Backtracking
Greedy
DP

🟠 STRONG
Sorting
Queue
K-way Merge
Trie
Dijkstra
Topological Sort
2D DP
Bit Manipulation

🟡 USE
Obscure data structures
Rare implementation variants

🟢 SKIM
Low-value historical/theoretical material

⚪ SKIP FOR NOW
Advanced competitive-programming techniques not required
for the internship/placement target.
```

---

# 36. DSA GOLDEN RULE

> **Never confuse exposure with mastery.**

The playlist gives exposure.

Practice creates skill.

Pattern recognition creates interview ability.

Independent solving creates reliability.

Revision creates retention.

Mock interviews create performance.

---

**END OF `04_DSA_SEQUENCE.md`**
