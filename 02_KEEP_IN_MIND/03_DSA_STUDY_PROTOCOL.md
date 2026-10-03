# 🧠 DSA STUDY PROTOCOL

> **Purpose:** Define exactly how DSA is to be learned, practiced, revised, and retained throughout the career roadmap.

---

## 1. DSA'S ROLE IN THE ROADMAP

DSA is one of the **primary pillars** of the roadmap.

The objective is **not**:

> "Finish a DSA course."

The objective is to become capable of:

1. Understanding a problem.
2. Identifying the underlying pattern.
3. Choosing an appropriate data structure/algorithm.
4. Deriving a solution.
5. Implementing it cleanly in Java.
6. Analyzing time and space complexity.
7. Explaining the solution in an interview.
8. Recognizing variations of the same pattern in unfamiliar problems.

---

# 2. THE DSA LEARNING STACK

DSA will be learned through multiple complementary layers.

```text
JAVA FOUNDATION
      ↓
DSA CONCEPTS
      ↓
KUNAL KUSHWAHA
      ↓
ITSRUNTYM PATTERN RECOGNITION
      ↓
NEETCODE 150
      ↓
LEETCODE PRACTICE
      ↓
REVISION + PATTERN RECOGNITION
      ↓
INTERVIEW PROBLEM SOLVING
```

These resources are **not independent courses to finish one after another**.

They serve different purposes.

### Telusko / Java foundation

Provides the Java language knowledge required to implement DSA comfortably.

### Kunal Kushwaha

Provides structured DSA learning and Java-based problem solving.

### ItsRunTym

Provides **pattern recognition**.

Its purpose is to help answer:

> "What technique does this problem want?"

### NeetCode 150

Provides a curated problem set and problem-solving progression.

### LeetCode

Provides the actual long-term practice environment.

---

# 3. LANGUAGE RULE

## DSA LANGUAGE = JAVA

All serious DSA implementation should ultimately be done in **Java**.

Python may occasionally be used to understand an idea, but it should not become the primary implementation language.

The reason is alignment with:

* placement preparation
* Java/Spring backend
* interview coding
* Kunal's Java material
* the primary career stack

---

# 4. THE DSA LEARNING CYCLE

Every important DSA topic should follow this cycle:

```text
1. Learn concept
       ↓
2. Understand intuition
       ↓
3. Learn implementation
       ↓
4. Write implementation yourself
       ↓
5. Learn complexity
       ↓
6. Solve guided problems
       ↓
7. Solve problems independently
       ↓
8. Identify pattern
       ↓
9. Revise
       ↓
10. Re-solve representative problems
```

Do not skip directly from watching a video to watching another video.

---

# 5. THE "UNDERSTAND → IMPLEMENT → APPLY" RULE

For every major data structure or algorithm:

### Stage A — Understand

You should know:

* what it is
* why it exists
* what problem it solves
* how it works conceptually
* its important operations
* its limitations

### Stage B — Implement

You should be able to write the implementation yourself.

Examples:

* array traversal
* binary search
* linked list operations
* stack
* queue
* heap
* tree traversal
* graph representation
* BFS
* DFS

### Stage C — Apply

You should solve problems using the concept.

---

# 6. WHAT MUST BE MEMORIZED

Do **not** memorize complete solutions blindly.

Memorize only things that should become automatic.

### Memorize

* fundamental definitions
* important properties
* common operation complexities
* standard traversal orders
* standard algorithm templates
* common invariants
* common edge cases
* syntax that is repeatedly required
* recognition cues for common patterns

Examples:

```text
Binary Search → O(log N)

HashMap average lookup → O(1)

Stack → LIFO

Queue → FIFO

BFS → Queue

DFS → Stack/Recursion
```

### Do NOT memorize

* complete LeetCode solutions
* arbitrary variable names
* long code without understanding
* solutions to individual problems as isolated facts

---

# 7. COMPLEXITY IS NOT OPTIONAL

For every important problem, explicitly determine:

```text
Time Complexity:
Space Complexity:
```

Initially, use rough reasoning.

Later, become capable of explaining **why**.

Example:

```text
Single loop over N elements
→ O(N)

Nested independent loops
→ O(N²)

Repeated halving
→ O(log N)

Sorting + linear scan
→ O(N log N)
```

---

# 8. DSA PROBLEM-SOLVING PROTOCOL

Every serious problem follows this procedure.

## STEP 1 — Read the problem

Do not immediately code.

Determine:

* input
* output
* constraints
* special conditions
* duplicates?
* sorted?
* negative values?
* empty input?
* expected complexity?

---

## STEP 2 — Restate the problem

Explain it to yourself in simple language.

If you cannot restate it, you probably don't understand it.

---

## STEP 3 — Think of brute force

Ask:

> "What is the most obvious solution?"

Do this even if you already suspect the optimal approach.

This teaches optimization.

---

## STEP 4 — Identify the bottleneck

Ask:

> "Why is the brute-force solution too slow?"

This is where the pattern usually begins to emerge.

---

## STEP 5 — Look for clues

Ask:

### Array?

Could it be:

* HashMap
* Two Pointers
* Sliding Window
* Prefix Sum
* Binary Search
* Sorting

### Linked List?

Could it be:

* Fast/Slow Pointer
* Reversal
* Dummy Node

### Tree?

Could it be:

* DFS
* BFS
* recursion
* subtree calculation

### Graph?

Could it be:

* BFS
* DFS
* Dijkstra
* Topological Sort
* Union-Find

### Optimization?

Could it be:

* Greedy
* DP
* Binary Search on Answer

---

# 9. THE 15-MINUTE RULE

When learning a problem:

### Easy

Attempt independently before looking at the solution.

### Medium

Give yourself a meaningful attempt.

### Hard

Do not waste an unreasonable amount of time staring at it.

The goal is learning, not suffering.

If genuinely stuck:

```text
Attempt
↓
Identify where stuck
↓
Take a small hint
↓
Attempt again
↓
Read explanation if necessary
↓
Close explanation
↓
Implement yourself
```

---

# 10. THE "NO PASSIVE SOLVING" RULE

Watching someone solve 100 problems does **not** mean you can solve 100 problems.

For every important problem:

> **You must personally write the solution.**

Typing along with a video does not count as independent solving.

---

# 11. AFTER SEEING A SOLUTION

If you had to look at the solution:

Do NOT immediately mark the problem as solved.

Instead:

```text
Understand solution
↓
Close solution
↓
Reconstruct approach
↓
Code from memory
↓
Test
↓
Explain complexity
↓
Revisit later
```

---

# 12. PATTERN RECOGNITION

Eventually every problem should trigger questions such as:

> "What pattern is this?"

Examples:

```text
Sorted array + pair relationship
→ Two Pointers

Contiguous subarray + changing condition
→ Sliding Window

Repeated range-sum queries
→ Prefix Sum

Fast/slow movement
→ Two Pointers / Fast-Slow

Top K
→ Heap / Priority Queue

Level-by-level tree traversal
→ BFS

Shortest path in weighted graph with non-negative weights
→ Dijkstra

Dependencies / prerequisites
→ Topological Sort

Repeated overlapping subproblems
→ DP
```

These associations should become increasingly automatic.

---

# 13. DSA NOTE STRUCTURE

For every major DSA topic, maintain:

```text
CONCEPT
INTUITION
CORE TEMPLATE
COMPLEXITY
WHEN TO USE
WHEN NOT TO USE
RECOGNITION CUES
EDGE CASES
COMMON MISTAKES
REPRESENTATIVE PROBLEMS
```

---

# 14. DSA MISTAKE LOG

Every meaningful mistake should be recorded.

Examples:

```text
Mistake:
Forgot to shrink sliding window.

Why:
Did not maintain window invariant.

Fix:
Whenever condition becomes invalid, shrink until valid.
```

The mistake log should be reviewed during revision.

---

# 15. DSA REVISION

Revision should include:

### Concept revision

Can you explain the idea?

### Template revision

Can you write the basic implementation?

### Recognition revision

Can you identify the pattern from a new problem?

### Problem revision

Can you re-solve representative problems?

---

# 16. DSA MASTERY STANDARD

A topic is **not complete because the video is complete**.

A topic is considered learned when you can:

* explain it
* implement it
* state its complexity
* recognize when to use it
* solve representative problems
* identify common variations
* avoid previously documented mistakes

---

# 17. IMPORTANT PRINCIPLE

> **We are training problem-solving ability, not video-completion ability.**

The number of videos completed is a progress metric.

It is **not the final goal**.

---

# 18. FINAL DSA PIPELINE

```text
Learn
↓
Understand
↓
Implement
↓
Practice
↓
Recognize
↓
Apply
↓
Revise
↓
Re-solve
↓
Interview
```

This cycle continues throughout the roadmap.
