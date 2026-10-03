# 🧠 DSA Problem-Solving Protocol

> **Purpose:** This is the standard operating procedure for solving DSA problems throughout the entire roadmap.
>
> It applies to problems from Kunal Kushwaha, ItsRunTym, NeetCode 150, LeetCode, college preparation, mock interviews, and placement preparation.

---

# 1. The Core Philosophy

The objective of DSA preparation is **not**:

> "See a problem → remember a solution → reproduce it."

The objective is:

> **Problem → constraints → structure → pattern → approach → implementation → verification → reflection → retention**

The most valuable skill is not memorizing individual LeetCode solutions.

It is learning to answer:

> **"Why is this the correct approach for this problem?"**

---

# 2. The Golden Rule

> ## **Always attempt to think before consuming the solution.**

The struggle is part of the learning.

However, struggle should be **productive**, not endless.

We therefore use a controlled struggle protocol.

---

# 3. Phase 0 — Identify the Problem's Context

Before solving, record:

* Problem name
* Source
* Topic/pattern if already known
* Difficulty
* Date attempted

Example:

```text
Problem:
Two Sum

Source:
NeetCode 150

Topic:
Arrays & Hashing

Difficulty:
Easy

Date:
2026-09-XX
```

Do not immediately look at the solution.

---

# 4. Phase 1 — Understand the Problem

Read the statement carefully.

Determine:

### Input

What is provided?

### Output

What exactly must be returned?

### Constraints

What limits exist?

For example:

```text
n ≤ 10
```

and

```text
n ≤ 100,000
```

imply completely different algorithmic possibilities.

---

## Ask yourself

* Can values repeat?
* Is the input sorted?
* Is it guaranteed to contain something?
* Can negative values occur?
* Is the answer unique?
* Does order matter?
* Can the input be modified?
* Is extra memory allowed?
* Are there multiple test cases?

---

# 5. Phase 2 — Restate the Problem

Before coding, explain the problem to yourself in simple language.

Example:

> "I need to find two indices whose values add up to the target."

If you cannot explain the problem simply, you are not ready to solve it.

---

# 6. Phase 3 — Construct the Brute Force

Before searching for the optimal solution, ask:

> "What is the simplest solution I can think of?"

This is extremely important.

The brute-force approach teaches:

* what the problem fundamentally asks
* why it is expensive
* what repeated work exists
* where optimization opportunities appear

---

## Example thought process

```text
Try every pair
      ↓
O(n²)
      ↓
Repeated searching
      ↓
Can previous information be stored?
      ↓
HashMap?
      ↓
O(n)
```

The optimized solution becomes a consequence of reasoning rather than memorization.

---

# 7. Phase 4 — Complexity Check

Estimate the brute-force complexity.

Ask:

```text
Time?
Space?
```

Then compare it with the constraints.

### Typical reasoning

```text
n ≈ 10
→ O(n²) may be fine

n ≈ 10⁵
→ O(n²) is probably too slow

n ≈ 10⁶
→ likely need O(n) or O(n log n)
```

These are heuristics, not absolute laws.

---

# 8. Phase 5 — Search for Structural Clues

Now inspect the problem for clues.

Ask:

### Array/string clues

* sorted?
* contiguous?
* frequency?
* duplicates?
* pairs?
* subarray?
* substring?

### Linked list clues

* cycle?
* middle?
* intersection?
* reverse?

### Tree clues

* level?
* path?
* depth?
* subtree?
* ancestor?

### Graph clues

* reachability?
* shortest path?
* dependency?
* connected components?

### Optimization clues

* minimum?
* maximum?
* number of ways?
* best possible?
* choose/not choose?

---

# 9. Pattern Recognition

Use the pattern library.

Potential signals:

```text
Sorted + pair condition
→ Two Pointers / Binary Search

Contiguous subarray/substring
→ Sliding Window / Prefix Sum

Repeated range sum
→ Prefix Sum

Cycle
→ Fast & Slow Pointers

"Top K"
→ Heap / Priority Queue

Shortest path + weighted graph
→ Dijkstra

Prerequisites/dependencies
→ Topological Sort

Overlapping intervals
→ Merge Intervals

Generate every valid combination
→ Backtracking

Overlapping subproblems + optimization
→ Dynamic Programming

Local optimal choice
→ Greedy
```

These are **clues**, not automatic answers.

---

# 10. The Pattern Confirmation Test

Before committing to a pattern, ask:

> **"Why does this pattern fit?"**

Do not say:

> "This looks like sliding window."

Instead say:

> "The problem asks about a contiguous range, and the validity of the range can be maintained incrementally as the right boundary moves, so sliding window is appropriate."

That is genuine pattern recognition.

---

# 11. Phase 6 — Attempt the Optimized Approach

Now formulate:

1. Data structure
2. Algorithm
3. State/invariant
4. Loop structure
5. Edge cases
6. Complexity

Do not immediately code.

Explain the algorithm in plain language first.

---

# 12. Phase 7 — Write Pseudocode

Before Java implementation, write a short mental or written pseudocode.

Example:

```text
for each element:
    determine what information is needed
    check stored information
    if answer found:
        return answer
    store current information
```

Pseudocode should be concise.

It is not another programming assignment.

---

# 13. Phase 8 — Code Independently

Now implement in Java.

Rules:

* Type the code yourself.
* Do not copy/paste a solution.
* Do not keep the editorial open while coding.
* Use your own variable names where reasonable.
* Keep the implementation clean.
* Do not prematurely optimize syntax.

---

# 14. Phase 9 — Test Manually

Before submitting, test:

### Normal case

Typical input.

### Smallest case

Minimum valid input.

### Largest realistic case

Tests complexity.

### Edge cases

Examples:

* empty/single element where allowed
* duplicates
* negative numbers
* zero
* already sorted
* reverse sorted
* all identical
* answer at beginning
* answer at end
* no answer

---

# 15. Phase 10 — Complexity Analysis

Every meaningful DSA problem should end with:

```text
Time Complexity: O(...)
Space Complexity: O(...)
```

But do not memorize complexity without understanding where it comes from.

Ask:

> "Which operation is responsible for this complexity?"

---

# 16. The Controlled Struggle Protocol

We use time limits to prevent both premature solution-viewing and pointless suffering.

### First few minutes

Try independently.

Do not search.

### If stuck

Re-read constraints.

Try:

* brute force
* examples
* smaller cases
* drawing
* alternate representation
* known data structures

### If still stuck

Ask:

> "What pattern could this belong to?"

Look only for a **hint**, not the full solution.

### If still completely stuck

Use the smallest amount of external help necessary.

Possible sequence:

```text
Problem
  ↓
Hint
  ↓
Pattern identification
  ↓
Approach
  ↓
Pseudocode
  ↓
Implementation
```

Avoid jumping directly to:

```text
Problem
  ↓
Full code
```

---

# 17. If You Look at the Solution

Looking at a solution is **not failure**.

The mistake is looking at it and then counting the problem as mastered.

Instead:

```text
See solution
     ↓
Close solution
     ↓
Explain approach from memory
     ↓
Implement yourself
     ↓
Test
     ↓
Record why you were stuck
     ↓
Re-solve later
```

---

# 18. Classify the Type of Failure

After every difficult problem, identify what actually went wrong.

### Type A — Concept gap

> "I didn't know this technique."

### Type B — Pattern-recognition gap

> "I knew the technique but couldn't recognize it."

### Type C — Algorithm gap

> "I recognized the pattern but couldn't derive the algorithm."

### Type D — Implementation gap

> "I understood the algorithm but couldn't code it."

### Type E — Debugging gap

> "The approach was correct but my implementation failed."

### Type F — Complexity gap

> "My solution worked but was too slow."

### Type G — Edge-case gap

> "I didn't consider an important case."

### Type H — Recall gap

> "I knew this before but couldn't retrieve it."

This classification determines what should be revised.

---

# 19. The "Explain Before Moving On" Rule

For important problems, you should eventually be able to explain:

```text
Problem
↓
Brute force
↓
Why brute force is insufficient
↓
Pattern
↓
Optimal idea
↓
Algorithm
↓
Implementation
↓
Complexity
↓
Edge cases
```

If you can only reproduce the code, the learning is incomplete.

---

# 20. The Re-Solve Protocol

A solved problem is not finished forever.

For important problems:

### Re-solve 1

Without looking at the solution.

### Re-solve 2

After some forgetting.

### Re-solve 3

During mixed practice/interview preparation.

The exact intervals are managed by the revision system.

---

# 21. The Pattern Extraction Rule

After solving a useful problem, record:

```text
Pattern:
Recognition clue:
Core idea:
Template:
Important invariant:
Common mistake:
Variation:
Related problems:
```

Example:

```text
Pattern:
Two Pointers

Recognition clue:
Sorted array + pair condition

Core idea:
Move pointers according to comparison with target.

Common mistake:
Moving the wrong pointer.

Variation:
Opposite-direction pointers / same-direction pointers
```

This transforms individual problems into reusable knowledge.

---

# 22. The "Do Not Memorize Solutions" Rule

Do not memorize:

```text
for (...) {
    ...
}
```

as an isolated code sequence.

Instead memorize:

* the invariant
* the decision rule
* the pattern
* the template
* the reasoning

Then reconstruct the implementation.

---

# 23. When a Template Is Appropriate

Templates are useful for recurring structures:

* Binary Search
* BFS
* DFS
* Union-Find where applicable
* Sliding Window
* Two Pointers
* Backtracking
* Dijkstra
* Topological Sort
* Heap-based Top K
* Tree traversals

But templates are **starting points**, not substitutes for reasoning.

---

# 24. The Problem Difficulty Ladder

Problems should generally progress:

```text
Concept example
      ↓
Easy
      ↓
Easy variation
      ↓
Medium
      ↓
Medium variation
      ↓
Mixed/unfamiliar
      ↓
Interview-style
```

Hard problems are not automatically necessary.

Quality and pattern coverage matter more than collecting difficult problems.

---

# 25. The "Move On" Rule

Move forward when:

* you understand the concept
* you can implement the core pattern
* you have solved enough representative problems
* major mistakes are understood
* you can recognize the pattern in familiar contexts

Do **not** wait for:

> "I can solve every possible problem."

That state never arrives.

---

# 26. The "Return Later" Rule

Return to a topic when:

* the same mistake appears repeatedly
* you cannot recognize the pattern
* implementation repeatedly fails
* complexity analysis is weak
* you forgot the core approach
* interview practice exposes a gap

Weakness is information.

---

# 27. Mixed Practice

Once multiple patterns are learned, stop practicing only by topic.

Instead mix:

```text
Two Pointers
Sliding Window
HashMap
Binary Search
Stack
Prefix Sum
```

This is where genuine pattern recognition develops.

The question changes from:

> "Which technique did the chapter teach?"

to:

> **"Which technique does this problem require?"**

---

# 28. Source-Specific Rule

### Kunal Kushwaha

Primary role:

> **Concepts + implementation + DSA foundation**

### ItsRunTym

Primary role:

> **Pattern recognition + interview-oriented problem-solving**

### NeetCode 150

Primary role:

> **Curated high-value problem practice**

### LeetCode

Primary role:

> **Independent practice + interview simulation + long-term problem bank**

These resources should **not** be treated as four independent courses.

---

# 29. The Complete Protocol

```text
READ
 ↓
UNDERSTAND
 ↓
IDENTIFY CONSTRAINTS
 ↓
RESTATE
 ↓
BRUTE FORCE
 ↓
COMPLEXITY
 ↓
STRUCTURAL CLUES
 ↓
PATTERN HYPOTHESIS
 ↓
CONFIRM PATTERN
 ↓
DESIGN OPTIMAL APPROACH
 ↓
PSEUDOCODE
 ↓
CODE IN JAVA
 ↓
TEST
 ↓
COMPLEXITY ANALYSIS
 ↓
EXPLAIN
 ↓
RECORD INSIGHT/MISTAKE
 ↓
RE-SOLVE
 ↓
MIX INTO FUTURE PRACTICE
```

---

# 30. Golden Rules

### Rule 1

**Think before searching.**

### Rule 2

**Understand the constraints before choosing an algorithm.**

### Rule 3

**Know the brute force before optimizing.**

### Rule 4

**Recognize patterns rather than memorizing solutions.**

### Rule 5

**Code independently.**

### Rule 6

**Analyze complexity.**

### Rule 7

**Record mistakes.**

### Rule 8

**Re-solve important problems.**

### Rule 9

**Mix patterns after learning them.**

### Rule 10

> **The goal is not to remember 300 solutions. The goal is to become capable of deriving the right solution to a new problem.**
