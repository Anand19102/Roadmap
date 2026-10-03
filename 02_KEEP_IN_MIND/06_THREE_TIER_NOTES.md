# 🧩 THREE-TIER NOTES SYSTEM

> **Purpose:** Maintain the right balance between active learning, reference material, and executable knowledge.

---

# TIER 1 — ✍️ HANDWRITTEN / ACTIVE NOTES

## Purpose

Used for:

* difficult concepts
* diagrams
* intuition
* formulas
* things you personally struggle to understand
* active recall
* important interview concepts

These should be **short and personal**.

---

## What belongs here?

Examples:

```text
Why binary search works
Sliding window invariant
HashMap collision intuition
OOP relationships
BFS vs DFS
DP state definition
```

Handwritten notes should capture **your understanding**, not the instructor's wording.

---

# TIER 2 — 💻 DIGITAL REFERENCE NOTES

Stored as Markdown.

Purpose:

* long-term reference
* organized knowledge
* revision
* interview preparation
* comparisons
* detailed explanations

Examples:

```text
05_DSA/
02_ARRAYS_HASHING/
README.md
```

Digital notes can be more detailed than handwritten notes.

---

# TIER 3 — 💻 CODE / IMPLEMENTATION

This is the most important layer for programming.

Store:

* implementations
* templates
* solutions
* experiments
* project code
* reusable snippets

Example:

```text
05_DSA/
06_BINARY_SEARCH/
    README.md
    BinarySearch.java
    LowerBound.java
    UpperBound.java
    variations.md
```

---

# 4. THE THREE TIERS WORK TOGETHER

```text
LEARNING
   ↓
Handwritten understanding
   ↓
Digital structured reference
   ↓
Actual code
   ↓
Practice
   ↓
Revision
```

---

# 5. WHAT NOT TO DO

Do not:

* rewrite the same thing three times
* copy entire videos
* copy entire transcripts
* make handwritten notes for trivial syntax
* create massive notes before coding

The three tiers are **different representations**, not three copies.

---

# 6. EXAMPLE — BINARY SEARCH

### Tier 1

Handwritten:

```text
Search space repeatedly halves.

Invariant:
target, if present, remains inside search range.
```

### Tier 2

Markdown:

* definition
* intuition
* variants
* complexity
* recognition
* edge cases
* common mistakes

### Tier 3

Java:

```text
BinarySearch.java
LowerBound.java
UpperBound.java
```

---

# 7. WHEN TO USE EACH TIER

| Situation                | Primary tier           |
| ------------------------ | ---------------------- |
| Difficult intuition      | Handwritten            |
| Long-term reference      | Markdown               |
| Syntax                   | Code                   |
| Algorithm implementation | Code                   |
| Interview revision       | Markdown + handwritten |
| DSA practice             | Code                   |
| Project learning         | Code + Markdown        |
| Mistakes                 | Markdown               |
| Formula                  | Handwritten + Markdown |

---

# 8. CORE PRINCIPLE

> **If you cannot implement it, your notes don't count as mastery.**

For programming topics, executable knowledge is the final test.
