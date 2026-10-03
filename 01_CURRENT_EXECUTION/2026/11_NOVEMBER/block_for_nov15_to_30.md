# 📅 MEC CAREER ROADMAP

## NOVEMBER 15–30, 2026 — BIWEEKLY EXECUTION BLOCK

> **Block Type:** Flexible biweekly target block
> **Primary Purpose:** Continue the established roadmap from the Nov 14 checkpoint
> **Execution Rule:** This block defines **WHAT should be completed**, not which calendar day each task must happen.
> **Day-wise plans will be generated dynamically from this block according to actual college workload, exam announcements, gym schedule, available study time, and progress.**

---

# 0. BLOCK POSITION IN THE MASTER ROADMAP

```text
JAVA FOUNDATION
      ↓
DSA FOUNDATION
      ↓
SQL + DATABASE FOUNDATION
      ↓
CORE CS
      ↓
SPRING / SPRING BOOT
      ↓
BACKEND
      ↓
PROJECTS
      ↓
INTERNSHIP / PLACEMENT
      ↓
SYSTEM DESIGN
      ↓
DISTRIBUTED SYSTEMS / CLOUD
```

### Current strategic phase

```text
                 CURRENT PHASE
                      │
                      ▼
        ┌──────────────────────────┐
        │  FOUNDATION CONSOLIDATION │
        └──────────────────────────┘
                      │
        ┌─────────────┼─────────────┐
        ▼             ▼             ▼
      JAVA           DSA       SQL / DBMS
        │             │             │
        └─────────────┼─────────────┘
                      ▼
                 CORE CS
                      │
                      ▼
             BACKEND TRANSITION
```

The immediate objective is **not** to rush into Spring Boot.

The current objective is to finish the remaining Java foundation, complete the remaining major DSA pattern sequence, and strengthen SQL/DBMS/Core CS enough that the later backend phase rests on a solid base.

---

# 1. STARTING CHECKPOINT — NOVEMBER 14

The block begins from the following established position.

## 🟦 JAVA

### Completed endpoint

**Telusko Lecture 127 — Method Reference**

The following broader sequence has been covered:

* OOP foundation
* Inheritance
* Polymorphism
* Packages/access modifiers
* `final`
* Object class
* Upcasting/downcasting
* Wrapper classes
* Project 1
* Abstract classes
* Inner/anonymous classes
* Interfaces
* Enums
* Annotations
* Functional interfaces
* Lambda expressions
* Exceptions
* User input
* Threads
* Collection API
* ArrayList
* Set
* Map
* Comparator / Comparable
* Generics
* Date & Time
* Stream API
* Optional
* Method references

### Next exact Telusko sequence

**128 → 139**

```text
128. Fundamentals Before IO Operation
129. Creating Files and Directories Using the File Class
130. More on the File Class
131. Writing Data to a File Using FileWriter
132. Reading Data from a File Using FileReader
133. BufferedWriter and FileWriter
134. BufferedReader and FileReader
135. Write Operation with PrintWriter
136. Introduction to Serialization and Deserialization
137. Serialization
138. Deserialization
139. Transient (Selective Serialization)

Quiz 2 — Advance Java Quiz
```

---

# 2. 🟦 JAVA — NOV 15–30 TARGET

## Primary objective

### Finish the remaining Telusko Java sequence:

**Lecture 128 → Lecture 139**

followed by:

**Quiz 2 — Advance Java Quiz**

---

## Java topic progression

### Phase J1 — Java I/O foundations

**128. Fundamentals Before IO Operation**

Master the purpose and basic model of Java I/O.

Target understanding:

* Why I/O exists
* Input vs output
* Files as persistent storage
* Basic Java I/O terminology
* Relationship between streams and files

**Mastery target:** 🟠 STRONG UNDERSTANDING

---

### Phase J2 — File handling

**129. Creating Files and Directories Using the File Class**

Target:

* File objects
* File paths
* File creation
* Directory creation
* Basic filesystem interaction

**Mastery target:** 🟡 LEARN/USE

---

**130. More on the File Class**

Target:

* File metadata
* File existence
* File/directory checks
* Basic file manipulation concepts

**Mastery target:** 🟡 LEARN/USE

---

### Phase J3 — Writing and reading files

**131. Writing Data to a File Using FileWriter**

Target:

* FileWriter
* Writing character data
* Resource handling
* Basic file-writing implementation

**Mastery target:** 🟠 STRONG UNDERSTANDING

---

**132. Reading Data to a File Using FileReader**

Target:

* FileReader
* Reading character data
* Basic read workflow
* Handling end-of-file

**Mastery target:** 🟠 STRONG UNDERSTANDING

---

### Phase J4 — Buffered I/O

**133. BufferedWriter and FileWriter**

Understand:

* Why buffering exists
* BufferedWriter
* Relationship with FileWriter
* Practical use cases

**Mastery target:** 🟠 STRONG UNDERSTANDING

---

**134. BufferedReader and FileReader**

Understand:

* BufferedReader
* Relationship with FileReader
* Efficient reading
* Line-oriented reading

**Mastery target:** 🟠 STRONG UNDERSTANDING

---

### Phase J5 — PrintWriter

**135. Write Operation with PrintWriter**

Understand:

* PrintWriter
* Convenient formatted/text output
* Difference from lower-level writers

**Mastery target:** 🟡 LEARN/USE

---

### Phase J6 — Serialization

**136. Introduction to Serialization and Deserialization**

Understand:

* What serialization means
* What deserialization means
* Why objects may need persistent representation
* Basic Java object persistence model

**Mastery target:** 🟠 STRONG UNDERSTANDING

---

**137. Serialization**

Implement:

* Serializable objects
* Object output
* Basic serialization workflow

**Mastery target:** 🟡 LEARN/USE → 🟠 if used confidently

---

**138. Deserialization**

Implement:

* Reading serialized objects
* Reconstructing objects
* Basic deserialization workflow

**Mastery target:** 🟡 LEARN/USE

---

**139. Transient (Selective Serialization)**

Understand:

* `transient`
* Fields excluded from serialization
* Why selective serialization matters

**Mastery target:** 🟡 LEARN/USE

---

## Java completion checkpoint

After 128–139:

### Must be able to:

* Explain basic Java I/O
* Create/read/write files
* Understand buffering
* Use common file-reading/writing classes
* Explain serialization/deserialization
* Explain `transient`
* Reproduce basic I/O code without blindly copying

### Do NOT over-invest in:

* obscure Java I/O APIs
* advanced filesystem APIs
* obscure serialization internals
* advanced concurrency beyond the already covered foundation

The purpose here is **placement/backend readiness**, not becoming a Java library specialist.

---

# 3. 🟧 JAVA CODING / REPRODUCTION REQUIREMENT

For this block, Java study is **not just watching Telusko**.

For each meaningful topic:

```text
WATCH
  ↓
UNDERSTAND
  ↓
WRITE SMALL CODE
  ↓
RUN IT
  ↓
MODIFY IT
  ↓
EXPLAIN IT
```

At minimum, reproduce examples involving:

* File creation
* Writing to a file
* Reading from a file
* Buffered reading/writing
* PrintWriter
* Serialization
* Deserialization
* transient field

### Java notes

Use the established three-tier note system:

1. **Handwritten concise notes**
2. **Source/transcript/reference notes where useful**
3. **Actual code**

Do not turn every lecture into huge notes.

---

# 4. 🟩 DSA — NOV 15–30 TARGET

## Current DSA position

Completed/covered:

```text
1. Two Pointers
2. Fast & Slow — DEFERRED
3. Sliding Window
4. Prefix Sum
5. Merge Intervals
6. Binary Search
7. Sorting Algorithms
8. HashMaps / Internal Working
9. Stack
10. Queue
11 & 13. Heap / Top K Elements
12. K-way Merge
14. Trees / Traversals
15. DFS
16. BFS
17. Graphs & Representation
```

### Important exception

**Pattern 2 — Fast & Slow Pointers remains deliberately deferred.**

It should be revisited when Linked List work makes the pattern naturally useful.

Do **not** accidentally mark Pattern 2 as forgotten or completed.

---

# 5. DSA PRIMARY TARGET

## Pattern 18 — Dijkstra

### ItsRunTym

**18. Dijkstra — ~35 min**

Target understanding:

* Weighted graphs
* Shortest path concept
* Why BFS is insufficient for arbitrary positive edge weights
* Distance relaxation
* Priority queue / min-heap role
* Visited/finalized-state idea
* Complexity
* Java implementation

### Mastery target

🔴 **MASTER**

Because shortest-path algorithms are important for:

* graph interviews
* backend/system reasoning
* algorithmic problem solving
* understanding weighted graph problems

---

# 6. DSA — KUNAL KUSHWAHA MAPPING

Kunal Kushwaha remains the **concept/problem-solving reinforcement layer**.

For Dijkstra:

* Review Kunal's relevant graph/shortest-path material **if needed**
* Use it to reinforce the concept after the primary ItsRunTym lesson
* Do not create a second full linear DSA curriculum

### Important source rule

Exact Kunal lecture titles/numbers have **not** been supplied in our established data.

Therefore:

> **Do not invent Kunal video numbers or titles.**

Use targeted Kunal graph/shortest-path material only where it reinforces the active topic.

---

# 7. DSA — NEETCODE MAPPING

NeetCode is the **interview-problem layer**, not another linear course.

For the graph stage, activate relevant graph problems once the underlying concept is understood.

### Dijkstra / weighted shortest path

Potential relevant NeetCode graph practice includes:

* **Network Delay Time**

Use only after understanding the underlying shortest-path logic.

### Problem-solving protocol

For each selected problem:

```text
1. Read problem
2. Identify pattern
3. Attempt independently
4. Build brute-force idea if useful
5. Derive optimized approach
6. Code in Java
7. Test edge cases
8. Record mistake
9. Re-solve later
```

---

# 8. 🟧 DSA PRIMARY TARGET — PATTERN 19

## Topological Sort / Kahn's Algorithm

### ItsRunTym

**19. Topological Sort / Kahn's — ~59 min**

Target:

* Directed graphs
* Dependency relationships
* DAG
* Indegree
* Queue-based processing
* Kahn's algorithm
* Cycle detection
* Topological ordering
* Complexity
* Java implementation

### Mastery target

🔴 **MASTER**

---

## NeetCode mapping

Once the concept is understood:

* **Course Schedule**
* **Course Schedule II**

These naturally reinforce:

```text
dependency graph
      ↓
indegree
      ↓
topological processing
      ↓
cycle detection
```

---

## Kunal mapping

Use relevant graph/topological-sort material for targeted reinforcement.

Again:

> No invented Kunal lecture numbers/titles.

---

# 9. 🟧 DSA PRIMARY TARGET — PATTERN 20

## Trie

### ItsRunTym

**20. Trie — ~43 min**

Target:

* Prefix tree concept
* Trie node
* Children representation
* Insert
* Search
* Prefix search
* Complexity
* Java implementation
* When Trie is preferable to ordinary hashing/searching

### Mastery target

🟠 **STRONG UNDERSTANDING → 🔴 MASTER**

The user should be able to implement a basic Trie from scratch.

---

## NeetCode mapping

Relevant problem:

* **Implement Trie (Prefix Tree)**

This should be used as the primary interview implementation after learning the concept.

---

# 10. DSA END-OF-BLOCK CHECKPOINT

By the end of this block, the target is:

```text
Pattern 18 — Dijkstra                 🔴
Pattern 19 — Topological Sort/Kahn    🔴
Pattern 20 — Trie                     🟠/🔴
```

And:

```text
Kunal → targeted reinforcement
NeetCode → relevant graph/trie problems
Java → implementations
Revision → re-solve / recall
```

### Still intentionally pending

```text
21. Greedy
22. Dynamic Programming
23. Minimum Path Sum
24. Backtracking
25. Bitwise Operations
```

And separately:

```text
Fast & Slow Pointers
→ deferred until Linked List context
```

---

# 11. 🟦 SQL — NOV 15–30

## Current SQL position

Completed / covered:

```text
1. SQL Fundamentals
2. Filtering / Sorting
3. Aggregations
4. Joins
5. Subqueries
6. CTE
```

### Next:

```text
7. Window Functions
```

followed by:

```text
8. Database Concepts
```

---

# 12. SQL TARGET — WINDOW FUNCTIONS

## Core topics

Understand:

* What window functions are
* Difference between `GROUP BY` and window functions
* `OVER()`
* `PARTITION BY`
* `ORDER BY` inside windows
* Ranking functions
* `ROW_NUMBER`
* `RANK`
* `DENSE_RANK`
* Running totals
* Windowed aggregates
* `LAG`
* `LEAD`
* Common interview use cases

### Mastery target

🟠 **STRONG UNDERSTANDING**

The goal is not merely remembering syntax.

You should understand:

> **When would I use a window function instead of GROUP BY?**

---

## Practice

Use:

* SQL practice environment
* DataLemur
* HackerRank SQL where appropriate

### DataLemur role

Interview-oriented SQL problem solving.

### HackerRank role

Additional structured SQL practice.

Do not turn either platform into an obligation to complete every available problem.

---

# 13. SQL — DATABASE CONCEPTS

Begin/continue the conceptual database layer:

### Topics

* Database
* DBMS
* RDBMS
* Table
* Row
* Column
* Schema
* Relational model
* Primary key
* Foreign key
* Candidate key
* Super key
* Constraints
* Relationships

### Mastery targets

Basic definitions:

🟠 STRONG UNDERSTANDING

Obscure database details:

🟡 LEARN/USE

---

# 14. 🟨 DBMS / CORE CS — NOV 15–30

DBMS continues as the first formal Core CS subject.

## Current position

Covered/active:

* DBMS fundamentals
* Database/table/schema
* Keys
* Relationships
* ER model
* Normalization

---

# 15. DBMS TARGET

## Normalization consolidation

Target:

* Why normalization exists
* Redundancy
* Update anomaly
* Insert anomaly
* Delete anomaly
* Functional dependency
* 1NF
* 2NF
* 3NF
* BCNF awareness

### Mastery target

Normalization fundamentals:

🟠 **STRONG UNDERSTANDING**

Functional dependencies / BCNF:

🟡 → 🟠

The user should be able to look at a simple schema and explain:

> "What problem does normalization solve here?"

---

# 16. DBMS — NEXT LAYER

Begin moving toward:

## Transactions

Target concepts:

* Transaction
* Transaction states
* ACID
* Atomicity
* Consistency
* Isolation
* Durability

### Mastery target

🟠 **STRONG UNDERSTANDING**

---

## Concurrency awareness

Begin:

* Concurrency
* Why concurrent transactions create problems
* Basic locking idea
* Isolation concept

Detailed isolation levels can be expanded in the following block if time is limited.

### Mastery target

🟡 **LEARN/USE**

---

# 17. 🟨 APTITUDE — NOV 15–30

## Current position

The aptitude roadmap follows the exact:

**Rajesh Verma — Arihant — Fast Track OBJECTIVE ARITHMETIC**

sequence.

Already active:

### 1. Number System

pp. **1–21**

### 2. Number Series

pp. **22–41**

---

# 18. APTITUDE TARGET

## Complete / consolidate:

### Chapter 2 — Number Series

pp. **22–41**

Target:

* Pattern recognition
* Arithmetic patterns
* Difference patterns
* Multiplication/division patterns
* Mixed patterns
* Exam speed
* Accuracy

### Mastery target

🟠 **STRONG UNDERSTANDING**

The goal is not memorizing arbitrary examples.

The goal is rapidly identifying the rule.

---

## Next chapter

### Chapter 3 — Simple and Decimal Fractions

pp. **42–58**

Target:

* Fraction fundamentals
* Decimal-fraction conversion
* Simplification
* Comparison
* Arithmetic operations
* Common placement-test applications

### Mastery target

🟠 **STRONG UNDERSTANDING**

---

# 19. APTITUDE EXECUTION RULE

Do not let aptitude consume the primary study time.

Priority remains:

```text
JAVA
  ↓
DSA
  ↓
SQL / DBMS
  ↓
APTITUDE
```

Aptitude is currently a **consistent secondary habit**, not the central preparation track.

---

# 20. 🟩 COLLEGE / SEMESTER EXAM PROTECTION RULE

This block deliberately contains **NO assumption about the actual semester examination dates**.

If MEC announces examinations during this block:

### Normal mode

```text
Placement Roadmap
        +
College academics
```

### Heavy academic mode

```text
College academics
        ↓
Priority
        ↓
Placement roadmap reduced
```

### Exam mode

```text
SEMESTER EXAMS
      ↓
PRIMARY
      ↓
Placement roadmap → maintenance only
```

Maintenance may consist of:

* short DSA revision
* Java recall
* one small coding problem
* flashcard/Anki review
* no new heavy topic if academically inappropriate

The roadmap is **paused, not abandoned**.

---

# 21. 🏋️ GYM / COLLEGE COMPATIBILITY

No fixed daily gym assumption is built into this block.

Daily execution will adapt to:

* class hours
* assignments
* labs
* internal exams
* gym
* fatigue
* commute/walking time
* actual free hours

### Study priority on constrained days

If time is very limited:

```text
1. DSA
2. Java
3. SQL / DBMS
4. Aptitude
```

If more time is available:

```text
Java
+
DSA
+
SQL/DBMS
+
Aptitude
+
Revision
```

---

# 22. 🧠 FIVE-TIER MASTERY SYSTEM

Every topic in this block must be classified using the permanent system.

| Tier                    | Meaning                     | Required action                                  |
| ----------------------- | --------------------------- | ------------------------------------------------ |
| 🔴 MASTER               | Deep mastery                | Explain → reproduce → implement → solve → recall |
| 🟠 STRONG UNDERSTANDING | Interview/application ready | Understand → implement/use → explain             |
| 🟡 LEARN/USE            | Functional familiarity      | Know what/when/how                               |
| 🟢 SKIM                 | Recognition only            | Know what it is                                  |
| ⚪ SKIP FOR NOW          | Deliberately deferred       | Ignore until activated                           |

---

# 23. 🔴 MASTER THESE IN THIS BLOCK

The following deserve genuine mastery:

### Java

* Core file I/O workflow
* Reading/writing files
* Buffered I/O fundamentals

### DSA

* Dijkstra
* Topological Sort / Kahn's Algorithm
* Basic Trie implementation

### SQL

* Window-function fundamentals

### DBMS

* Normalization fundamentals
* ACID fundamentals

---

# 24. 🟠 UNDERSTAND WELL

* Java serialization/deserialization
* `transient`
* File class
* PrintWriter
* Database concepts
* Functional dependencies
* Concurrency basics
* Isolation concepts
* Aptitude Number Series
* Fractions

---

# 25. 🟡 DO NOT OVERSTUDY

* Obscure Java I/O APIs
* Advanced serialization internals
* Extremely obscure DBMS edge cases
* Advanced graph theory beyond the active patterns
* Rare aptitude tricks
* Every possible SQL function

---

# 26. 🔁 REVISION SYSTEM FOR THIS BLOCK

Every major new topic should have at least one later recall point.

Example:

```text
Learn Dijkstra
      ↓
Implement Dijkstra
      ↓
Solve problem
      ↓
Later: explain Dijkstra without notes
```

Likewise:

```text
Learn Trie
      ↓
Implement Trie
      ↓
Implement again from memory
```

And:

```text
Learn Window Functions
      ↓
Write queries
      ↓
Solve interview problem
      ↓
Recall GROUP BY vs WINDOW
```

---

# 27. 📝 MISTAKE LOG REQUIREMENT

Whenever something goes wrong, record:

```text
Topic:
Problem:
My approach:
Where I went wrong:
Correct idea:
Why I missed it:
Pattern to recognize next time:
```

Relevant locations:

```text
04_JAVA/MISTAKES/
05_DSA/MISTAKES/
08_SQL_DATABASES/MISTAKES/
07_CORE_CS/MISTAKES/
```

---

# 28. 💻 DSA IMPLEMENTATION REQUIREMENT

All DSA implementation for this block should be in **Java**.

Required implementations:

* Dijkstra
* Topological Sort using Kahn's Algorithm
* Trie

Do not merely watch implementations.

The desired progression is:

```text
Understand
   ↓
Read implementation
   ↓
Close source
   ↓
Rebuild
   ↓
Test
   ↓
Modify
   ↓
Explain
```

---

# 29. 🎯 NEETCODE RULE

NeetCode remains a **problem layer**, not a separate course.

Only activate a problem when its prerequisite concept is ready.

### Active mapping

| DSA topic        | NeetCode practice            |
| ---------------- | ---------------------------- |
| Dijkstra         | Network Delay Time           |
| Topological Sort | Course Schedule              |
| Topological Sort | Course Schedule II           |
| Trie             | Implement Trie (Prefix Tree) |

If a problem is too advanced relative to the current concept, defer it rather than forcing it.

---

# 30. 🎯 KUNAL RULE

Kunal remains the **conceptual reinforcement layer**.

For each active DSA topic:

```text
ItsRunTym
   ↓
Understand
   ↓
Kunal targeted reinforcement
   ↓
Java implementation
   ↓
NeetCode problem
```

Do not watch Kunal material just to increase the number of videos completed.

The objective is **mastery**, not course completion statistics.

---

# 31. 🚫 WHAT IS NOT A NOV 15–30 PRIORITY

These remain intentionally later:

### Backend

* Spring
* Spring Boot
* REST APIs
* JPA/Hibernate
* Authentication
* Microservices
* Docker
* Cloud

### Projects

Major project-building is not the main focus yet.

### System Design

Deferred until the relevant backend foundations exist.

### Distributed Systems

Deferred.

### Power BI

Not a current priority.

### Advanced Python/Data

Secondary to the primary Java/backend pathway.

---

# 32. 🧭 BLOCK COMPLETION DEFINITION

The block is considered successful **if the following sequence is substantially completed**, not merely if every planned minute was used.

## Java

```text
128 → 139
      ↓
Quiz 2
```

## DSA

```text
18. Dijkstra
      ↓
19. Topological Sort / Kahn
      ↓
20. Trie
```

with:

```text
Kunal reinforcement
+
NeetCode practice
+
Java implementation
```

## SQL

```text
Window Functions
      ↓
Database Concepts
```

## DBMS

```text
Normalization
      ↓
Functional Dependencies / BCNF awareness
      ↓
Transactions / ACID
      ↓
Concurrency / Isolation awareness
```

## Aptitude

```text
Number Series
      ↓
Simple & Decimal Fractions
```

---

# 33. 📊 END-OF-BLOCK TARGET STATE

| Area            | Nov 15 starting point | Nov 30 target                               |
| --------------- | --------------------- | ------------------------------------------- |
| 🟦 Java         | Lecture 127           | Lecture 139 + Quiz 2                        |
| 🟧 DSA          | Pattern 17            | Pattern 20                                  |
| 🟧 Fast & Slow  | Deferred              | Still deferred                              |
| 🟧 Kunal        | Graph reinforcement   | Dijkstra / Topological / Trie reinforcement |
| 🟧 NeetCode     | Graph stage           | Dijkstra + Topological + Trie problems      |
| 🟦 SQL          | CTE                   | Window Functions + Database Concepts        |
| 🟨 DBMS         | Normalization         | Normalization → ACID / Transactions         |
| 🟨 Aptitude     | Number Series         | Number Series + Simple/Decimal Fractions    |
| 🟩 Core CS      | DBMS active           | DBMS strengthened                           |
| ⚪ Spring Boot   | Not started           | Still deferred                              |
| ⚪ Projects      | Not started formally  | Still deferred                              |
| ⚪ System Design | Deferred              | Deferred                                    |
| ⚪ Cloud         | Deferred              | Deferred                                    |
| 🟩 Python/Data  | Secondary             | No major expansion                          |

---

# 34. 🔥 PRIORITY ORDER

When available time is limited, use this hierarchy:

## TIER 1 — NON-NEGOTIABLE CORE

```text
JAVA
DSA
```

## TIER 2 — IMPORTANT SECONDARY

```text
SQL
DBMS
```

## TIER 3 — MAINTAIN CONSISTENCY

```text
APTITUDE
REVISION
```

## TIER 4 — ONLY WHEN FOUNDATIONAL WORK IS UNDER CONTROL

```text
Backend
Projects
System Design
Cloud
```

---

# 35. ⏱️ FLEXIBLE TIME MODEL

The block does **not** assume one fixed number of study hours.

### If ~30–60 minutes are available

Choose:

* DSA revision/problem
* Java lecture + tiny reproduction
* SQL practice
* aptitude practice

### If ~1.5–2 hours are available

Choose:

```text
Primary:
Java OR DSA

Secondary:
SQL / DBMS

Finish:
short revision
```

### If ~2.5–3+ hours are available

Use:

```text
Java
+
DSA
+
SQL/DBMS
+
revision
```

### If a full free day appears

Use it for:

* difficult DSA implementation
* Java reproduction
* backlog clearance
* NeetCode
* SQL practice
* DBMS consolidation

Do **not** automatically add unrelated new subjects merely because extra time exists.

---

# 36. 🧩 DAILY EXECUTION RULE

When a day begins, the day-wise planner should inspect:

```text
1. Current completion state
2. Remaining Nov 15–30 targets
3. Available study time
4. College workload
5. Upcoming internal/semester exams
6. Gym schedule
7. Fatigue
8. Previous day's unfinished work
9. Revision due
```

Then generate that day's work.

### Therefore:

**The biweekly block is the map.**

**The daily plan is the route chosen according to current conditions.**

---

# 37. 🏁 NOVEMBER 30 CHECKPOINT

At the end of the block, perform a structured review.

## Java

Can I:

* explain the I/O model?
* create/read/write files?
* explain buffering?
* use BufferedReader/BufferedWriter?
* explain serialization?
* serialize/deserialize an object?
* explain transient?

## DSA

Can I:

* explain Dijkstra?
* implement Dijkstra?
* explain Kahn's algorithm?
* detect a cycle using topological processing?
* implement a Trie?
* recognize when these patterns apply?
* solve the mapped NeetCode problems?

## SQL

Can I:

* explain window functions?
* distinguish them from GROUP BY?
* use PARTITION BY?
* use ranking functions?
* use LAG/LEAD?
* solve a basic interview-style window-function problem?

## DBMS

Can I:

* explain normalization?
* identify common anomalies?
* explain functional dependency?
* distinguish 1NF/2NF/3NF/BCNF at the required level?
* explain ACID?
* explain why concurrency/isolation matter?

## Aptitude

Can I:

* recognize common Number Series patterns?
* solve them accurately under reasonable time pressure?
* handle basic/simple decimal fractions?

---

# 38. 📌 IMPORTANT ROADMAP INVARIANTS

These rules remain unchanged unless deliberately revised in the master roadmap.

### Java

**Telusko PDF supplied by the user is authoritative.**

Do not replace its lecture structure with online Telusko modules.

### DSA

**ItsRunTym's supplied 25-pattern syllabus is the primary pattern sequence.**

### Kunal

Concept/problem-solving reinforcement.

### NeetCode

Interview-problem layer.

### Striver

Secondary targeted problem bank, not another linear curriculum.

### SQL

SQL fundamentals → filtering → aggregation → joins → subqueries → CTE → windows → database concepts → deeper database engineering.

### Core CS

DBMS first, then OS/CN/SE/System Design according to the master roadmap.

### Aptitude

Follow the exact Rajesh Verma/Arihant chapter sequence.

### Python/Data/Power BI

Secondary track; do not allow it to displace the primary Java/backend pathway without a deliberate roadmap decision.

---

# 39. 🧠 FINAL BLOCK PHILOSOPHY

This block is **not a race to finish every item**.

The objective is:

> **Finish the right things in the right order, with enough mastery that the next layer becomes easier.**

The progression should therefore remain:

```text
JAVA FOUNDATION
       +
DSA FOUNDATION
       ↓
SQL + DBMS
       ↓
CORE CS
       ↓
SPRING BOOT
       ↓
BACKEND
       ↓
PROJECTS
       ↓
INTERNSHIP / PLACEMENT
       ↓
SYSTEM DESIGN
       ↓
DISTRIBUTED SYSTEMS / CLOUD
```

And the daily execution remains adaptive.

---

## ✅ NOVEMBER 15–30 SOURCE-OF-TRUTH SUMMARY

```text
JAVA
128 → 139 + Quiz 2

DSA
18 → Dijkstra
19 → Topological Sort / Kahn
20 → Trie

DEFERRED
Fast & Slow Pointers

KUNAL
Targeted reinforcement of active DSA topics

NEETCODE
Network Delay Time
Course Schedule
Course Schedule II
Implement Trie

SQL
Window Functions
Database Concepts

DBMS
Normalization
Functional Dependencies
BCNF awareness
Transactions
ACID
Concurrency / Isolation awareness

APTITUDE
Number Series
Simple and Decimal Fractions

CORE CS
DBMS remains the active formal Core CS subject

BACKEND / PROJECTS / SYSTEM DESIGN / CLOUD
Remain intentionally deferred

EXECUTION
Flexible
Exam-aware
College-aware
Gym-aware
Progress-aware
No fixed daily assumptions
```

**This block now becomes the basis for generating the actual day-wise schedule when you tell me what each day/week actually looks like.**
