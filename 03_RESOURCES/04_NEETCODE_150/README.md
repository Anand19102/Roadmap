# 🟨 NEETCODE 150 — INTERVIEW PROBLEM MASTERY

> **Role:** Interview problem set + validation layer
> **Status:** 🟡 CORE PRACTICE RESOURCE
> **Purpose:** Convert DSA knowledge into interview-solving ability.

---

# 1. OFFICIAL RESOURCE

[NeetCode 150 — Official Practice List](https://neetcode.io/practice/practice/neetcode150?utm_source=chatgpt.com)

The current official list contains:

* 150 problems
* 28 Easy
* 101 Medium
* 21 Hard

and 18 major categories.

---

# 2. WHY WE USE IT

NeetCode 150 is NOT our teaching course.

It is our:

> **problem-solving benchmark.**

The progression is:

```text
Learn concept
      ↓
Implement concept
      ↓
Learn pattern
      ↓
Solve representative problem
      ↓
Solve NeetCode problem
      ↓
Review
      ↓
Reattempt
```

---

# 3. IMPORTANT PREREQUISITE

NeetCode itself recommends learning concepts as they are encountered and prioritizing common/easier concepts before advanced topics.

Therefore:

> We do NOT force all 150 problems from the beginning.

We activate categories when the corresponding DSA foundation is ready.

---

# 4. OFFICIAL CATEGORY STRUCTURE

The current NeetCode 150 categories are:

1. Arrays & Hashing — 9
2. Two Pointers — 5
3. Sliding Window — 6
4. Stack — 6
5. Binary Search — 7
6. Linked List — 11
7. Trees — 15
8. Heap / Priority Queue — 7
9. Backtracking — 10
10. Tries — 3
11. Graphs — 13
12. Advanced Graphs — 6
13. 1-D Dynamic Programming — 12
14. 2-D Dynamic Programming — 11
15. Greedy — 8
16. Intervals — 6
17. Math & Geometry — 8
18. Bit Manipulation — 7

---

# 5. OUR LEARNING LEVELS

## 🔴 MASTER

Problems that represent highly reusable interview patterns.

You should eventually be able to:

* solve independently
* explain
* code cleanly
* analyze complexity
* recognize variants

## 🟠 STRONG

Important problems where the pattern should be understood even if the exact problem is not instantly solvable.

## 🟡 LEARN / USE

Useful representative problems.

## 🟢 SKIM

Low-frequency or highly specialized variants.

## ⚪ SKIP FOR NOW

Not currently required.

---

# 6. CATEGORY STRATEGY

## ARRAYS & HASHING

### Priority

🔴 MASTER

### Purpose

Build:

* frequency maps
* sets
* lookup optimization
* array reasoning
* prefix/suffix techniques

---

## TWO POINTERS

### Priority

🔴 MASTER

Use after:

* arrays
* sorting
* pointer reasoning

Connect directly to ItsRunTym L1.

---

## SLIDING WINDOW

### Priority

🔴 MASTER

Connect to ItsRunTym L3.

---

## STACK

### Priority

🔴 MASTER

Connect to:

* parentheses
* monotonic stack
* next greater element

---

## BINARY SEARCH

### Priority

🔴 MASTER

Do not memorize one binary-search loop.

Master:

* invariant
* boundaries
* monotonicity
* search-on-answer

---

## LINKED LIST

### Priority

🔴 MASTER

Connect to:

* fast/slow pointers
* reversal
* merging
* cycle detection

---

## TREES

### Priority

🔴 MASTER

Master:

* DFS
* BFS
* recursion
* BST
* tree properties

---

## HEAP / PRIORITY QUEUE

### Priority

🔴 MASTER

Connect to:

* top K
* scheduling
* K-way merge
* graph algorithms

---

## BACKTRACKING

### Priority

🔴 MASTER

Master the recursion-tree model.

---

## TRIES

### Priority

🟠 STRONG

Understand the structure and common interview use cases.

---

## GRAPHS

### Priority

🔴 MASTER

Master:

* representation
* DFS
* BFS
* connected components
* cycle detection
* topological sort
* shortest paths

---

## ADVANCED GRAPHS

### Priority

🟠 STRONG

Master the common interview algorithms.

Specialized algorithms can remain lower priority unless required.

---

## 1-D DP

### Priority

🔴 MASTER

Master:

* state
* recurrence
* memoization
* tabulation
* optimization

---

## 2-D DP

### Priority

🔴 MASTER

Master representative grid/string DP patterns.

---

## GREEDY

### Priority

🔴 MASTER

Focus on reasoning and proof intuition.

---

## INTERVALS

### Priority

🔴 MASTER

Strongly relevant because of recurring scheduling/overlap patterns.

---

## MATH & GEOMETRY

### Priority

🟠 STRONG → 🟡 SELECTIVE

Master commonly recurring interview mathematics.

Do not turn this into competitive-math preparation.

---

## BIT MANIPULATION

### Priority

🟠 STRONG

Master common XOR/bit tricks.

---

# 7. PROBLEM-SOLVING PROTOCOL

Every serious NeetCode problem follows this sequence.

### 1. Read the problem

Do not immediately watch the solution.

### 2. Restate it

Explain the problem in your own words.

### 3. Identify constraints

Ask:

* How large is N?
* Is O(N²) possible?
* Is sorting allowed?
* Is extra space allowed?
* Is the input sorted?
* Is there monotonicity?
* Are duplicates possible?

### 4. Attempt brute force

Even briefly.

### 5. Identify the pattern

Ask:

> What structure is this problem exposing?

### 6. Attempt independently

Use a meaningful struggle period.

### 7. Use hints before solutions

If available.

### 8. Study solution only when necessary

Then close it.

### 9. Re-code from scratch

No copy-paste.

### 10. Explain

You should be able to explain:

* approach
* correctness intuition
* complexity

### 11. Reattempt later

Use spaced revision.

---

# 8. THE “SOLVED” DEFINITION

A problem is NOT considered solved merely because:

```text
Accepted ✅
```

It becomes:

### 🟢 Seen

You watched/read a solution.

### 🟡 Understood

You can explain the approach.

### 🟠 Re-solved

You independently coded it.

### 🔴 Mastered

You can:

* recognize the pattern
* solve independently
* explain it
* modify it
* solve a variation

---

# 9. NO-SOLUTION-FIRST RULE

For important problems:

> **Attempt → struggle → hint → attempt → solution → close → re-code.**

Never:

> Open problem → immediately watch video → type code → submit.

---

# 10. NEETCODE + AI

AI may be used as a tutor.

AI must NOT replace thinking.

Good:

> “I think this is sliding window. Can you tell me whether my reasoning has a flaw without giving the solution?”

Bad:

> “Solve this and give me the Java code.”

For difficult problems, AI should progressively reveal:

1. clarification
2. hint
3. pattern
4. invariant
5. pseudocode
6. implementation

---

# 11. TRACKING

Each problem should eventually have:

```text
Problem
Pattern
Difficulty
First attempt date
Result
Mistake
Correct approach
Complexity
Reattempt date
Mastery level
```

Store mistakes in:

`05_DSA/MISTAKES/`

Store reusable templates in:

`05_DSA/TEMPLATES/`

Store pattern notes in:

`05_DSA/PATTERNS/`

---

# 12. COMPANY-SPECIFIC LAYER

NeetCode should later connect with company preparation.

The current NeetCode platform includes company-specific problem areas, including companies such as Google, Amazon, Meta, Microsoft, Oracle, TCS, Infosys and Zoho.

This becomes useful during the **internship/placement preparation phase**, not during the initial DSA foundation phase.

---

# 13. NEETCODE 150 IS NOT THE FINISH LINE

We do NOT need to solve:

> 150 problems → stop learning DSA.

Instead:

```text
Kunal
 ↓
ItsRunTym
 ↓
NeetCode 150
 ↓
LeetCode/company-specific problems
 ↓
Timed practice
 ↓
Mocks
 ↓
Interview readiness
```

---

# 14. SUCCESS CRITERION

The ultimate goal is not:

> **150/150 solved.**

It is:

> **Recognize → reason → implement → explain → adapt.**

That is what turns DSA preparation into interview ability.

---

# 15. FINAL RULE

NeetCode 150 is a **curated practice curriculum**, not another course that must be watched from beginning to end.

The Master Roadmap will determine:

* when each category activates
* which problems are priority
* which are revision problems
* which can be skipped
* when company-specific practice begins
* when timed practice begins

The Current Execution Plan will specify the **exact problems for each week**.
