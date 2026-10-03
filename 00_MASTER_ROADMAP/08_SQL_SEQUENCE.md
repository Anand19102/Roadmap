# 08 — SQL SEQUENCE

> **Roadmap role:** SQL is a core placement + backend skill.
> **Primary objective:** Become capable of writing, understanding, debugging and explaining SQL queries, while gradually understanding the database concepts required for backend development and technical interviews.
>
> **Primary practice resources:** DataLemur + HackerRank
> **Backend connection:** Spring Boot → JPA/Hibernate → relational database → transactions/indexing/query optimisation
> **Placement connection:** SQL assessments, technical interviews, DBMS questions and backend roles.

---

## 1. SQL's Position in the Overall Roadmap

SQL is **not** a subject that should be postponed until the backend phase is almost finished.

However, it also should **not compete with Java + DSA during the initial habit-building period**.

The intended progression is:

```text
Java Foundations
      ↓
DSA Foundations
      ↓
Basic SQL
      ↓
Intermediate SQL
      ↓
DSA + SQL running concurrently
      ↓
Spring Boot + Database Integration
      ↓
DBMS Concepts
      ↓
Advanced SQL
      ↓
SQL Interview Practice
      ↓
Backend Projects
      ↓
Internship / Placement Revision
```

SQL therefore becomes a **secondary but increasingly important parallel track**.

---

# 2. SQL Mastery Classification

| Level                   | Meaning for SQL                                                                                      |
| ----------------------- | ---------------------------------------------------------------------------------------------------- |
| 🔴 MASTER               | Must be able to write queries independently and explain the underlying concept                       |
| 🟠 STRONG UNDERSTANDING | Must understand thoroughly and solve normal interview questions; less emphasis on obscure edge cases |
| 🟡 LEARN / USE          | Learn enough to use correctly in projects and recognise in interviews                                |
| 🟢 SKIM                 | Understand the idea and syntax; don't spend disproportionate practice time                           |
| ⚪ SKIP FOR NOW          | Deliberately postponed unless a later role/project requires it                                       |

---

# 3. Phase I — SQL Fundamentals

## 3.1 SQL Basics

### Topics

* What SQL is
* Relational databases
* Tables
* Rows
* Columns
* Primary keys
* Foreign keys
* SQL statements
* Basic database terminology
* `SELECT`
* `FROM`
* `WHERE`
* `ORDER BY`
* `DISTINCT`
* `LIMIT`

### Classification

🟠 **STRONG UNDERSTANDING**

### Required outcome

You should be able to look at a table and independently write basic retrieval queries.

### Practice

Start with simple HackerRank/DataLemur questions.

Do not immediately jump into difficult interview problems.

---

# 4. Phase II — Filtering and Sorting

## 4.1 Filtering

Master:

* `WHERE`
* comparison operators
* `AND`
* `OR`
* `NOT`
* `IN`
* `BETWEEN`
* `LIKE`
* `IS NULL`
* `IS NOT NULL`

### Classification

🔴 **MASTER**

These are foundational SQL operations.

---

## 4.2 Sorting

Master:

* `ORDER BY`
* ascending order
* descending order
* multiple sort columns

### Classification

🔴 **MASTER**

---

# 5. Phase III — Aggregation

## Topics

* `COUNT`
* `SUM`
* `AVG`
* `MIN`
* `MAX`
* `GROUP BY`
* `HAVING`

### Classification

🔴 **MASTER**

### Critical distinction

You must understand:

```text
WHERE
    ↓
filters rows before grouping

GROUP BY
    ↓
creates groups

HAVING
    ↓
filters groups after aggregation
```

This distinction must become automatic.

---

# 6. Phase IV — Joins

Joins are one of the most important SQL topics for both placements and backend development.

## Topics

* INNER JOIN
* LEFT JOIN
* RIGHT JOIN
* FULL OUTER JOIN — conceptual understanding
* self joins
* joining multiple tables
* join conditions
* aliases

### Classification

🔴 **MASTER**

### Required ability

Given a database schema, you should be able to determine:

1. Which tables are required?
2. What relationship connects them?
3. Which join is appropriate?
4. Which columns should be selected?
5. Whether filtering occurs before or after aggregation?

---

# 7. Phase V — Subqueries

## Topics

* scalar subqueries
* subqueries in `WHERE`
* subqueries in `FROM`
* correlated subqueries
* `EXISTS`
* `NOT EXISTS`

### Classification

🟠 **STRONG UNDERSTANDING**

You should be able to recognise when a subquery is useful and solve standard interview-level problems.

Do not spend excessive time memorising unusual syntax.

---

# 8. Phase VI — CTEs

## Topics

* `WITH`
* single CTE
* multiple CTEs
* chaining CTEs
* using CTEs for query readability

### Classification

🟠 **STRONG UNDERSTANDING**

CTEs should become a normal tool for solving more complex DataLemur-style questions.

---

# 9. Phase VII — Window Functions

This is a major SQL interview skill.

## Topics

* concept of a window
* `OVER`
* `PARTITION BY`
* `ORDER BY`
* `ROW_NUMBER`
* `RANK`
* `DENSE_RANK`
* `LAG`
* `LEAD`
* running totals
* ranking within groups

### Classification

🔴 **MASTER**

### Priority

Very high for placement-oriented SQL.

The goal is not merely to recognise window functions.

You should be able to construct them independently.

---

# 10. Phase VIII — Database Concepts

SQL should now connect with DBMS.

## Topics

* relational model
* primary key
* candidate key
* foreign key
* constraints
* relationships
* one-to-one
* one-to-many
* many-to-many
* NULL
* referential integrity

### Classification

🟠 **STRONG UNDERSTANDING**

These topics should be reinforced again during DBMS preparation.

---

# 11. Phase IX — Normalization

## Topics

* functional dependency — conceptual understanding
* redundancy
* anomalies
* 1NF
* 2NF
* 3NF
* BCNF — interview-level understanding

### Classification

🟠 **STRONG UNDERSTANDING**

You should understand **why normalization exists**, not merely memorise definitions.

---

# 12. Phase X — Indexing

## Topics

* why indexes exist
* index lookup
* basic B-tree/B+ tree intuition
* clustered vs non-clustered concept
* advantages
* disadvantages
* situations where indexes help
* situations where excessive indexes hurt

### Classification

🟠 **STRONG UNDERSTANDING**

The goal is conceptual understanding rather than database-engine internals.

---

# 13. Phase XI — Transactions

## Topics

* transaction
* ACID
* atomicity
* consistency
* isolation
* durability
* commit
* rollback
* basic isolation-level concept

### Classification

🟠 **STRONG UNDERSTANDING**

This becomes particularly important once Spring Boot backend development begins.

---

# 14. Phase XII — Query Optimization

## Topics

* why queries become slow
* indexes
* unnecessary data retrieval
* filtering
* joins
* query execution concept
* `EXPLAIN` / execution-plan awareness

### Classification

🟡 **LEARN / USE → eventually 🟠**

Do not make database internals a major early priority.

---

# 15. SQL Practice Progression

```text
Basic SELECT questions
        ↓
Filtering
        ↓
Aggregation
        ↓
Joins
        ↓
Subqueries
        ↓
CTEs
        ↓
Window Functions
        ↓
Mixed interview questions
        ↓
Timed SQL practice
```

---

# 16. Practice Resources

## DataLemur

Primary use:

* interview-style SQL
* realistic analytical queries
* joins
* aggregation
* CTEs
* window functions

Use progressively rather than attempting random difficult questions immediately.

---

## HackerRank

Primary use:

* fundamentals
* syntax reinforcement
* structured progression
* timed practice

---

# 17. SQL + Backend Integration

SQL should become increasingly connected to:

```text
Java
 ↓
Spring Boot
 ↓
JDBC / ORM concepts
 ↓
JPA / Hibernate
 ↓
Entity relationships
 ↓
SQL queries
 ↓
Transactions
 ↓
Indexes
 ↓
Database-backed applications
```

Do not learn SQL as an isolated aptitude-style subject.

---

# 18. SQL Revision System

### First exposure

Understand concept + write examples.

### Short-term revision

Rewrite representative queries without looking.

### Weekly revision

Solve several mixed questions.

### Long-term revision

Maintain:

* query patterns
* mistakes
* confusing concepts
* frequently forgotten syntax
* interview questions

---

# 19. SQL Interview Readiness

Before internship/placement preparation becomes intense, you should be comfortable with:

* SELECT
* WHERE
* GROUP BY
* HAVING
* joins
* subqueries
* CTEs
* window functions
* keys
* normalization
* indexing
* transactions
* ACID
* basic query optimization

The exact question difficulty will be increased gradually.

---

# 20. SQL Roadmap Rule

> **Do not "finish SQL" once and abandon it.**

SQL is maintained as a recurring skill.

```text
Learn
 ↓
Practice
 ↓
Use in project
 ↓
Revise
 ↓
Interview questions
 ↓
Use again in backend
 ↓
Revisit weak areas
```

---

# 21. SQL Priority Summary

| Area                    | Priority |
| ----------------------- | -------: |
| SELECT / filtering      |       🔴 |
| Aggregation             |       🔴 |
| GROUP BY / HAVING       |       🔴 |
| Joins                   |       🔴 |
| Subqueries              |       🟠 |
| CTEs                    |       🟠 |
| Window functions        |       🔴 |
| Database relationships  |       🟠 |
| Normalization           |       🟠 |
| Indexing                |       🟠 |
| Transactions / ACID     |       🟠 |
| Query optimisation      |  🟡 → 🟠 |
| Deep database internals |       🟢 |

---

# 22. Final SQL Dependency Chain

```text
SQL Fundamentals
      ↓
Filtering + Sorting
      ↓
Aggregation
      ↓
Joins
      ↓
Subqueries
      ↓
CTEs
      ↓
Window Functions
      ↓
Relational DB Concepts
      ↓
Normalization
      ↓
Indexes
      ↓
Transactions
      ↓
Query Optimization
      ↓
DataLemur / HackerRank
      ↓
Spring Boot Database Integration
      ↓
Backend Projects
      ↓
Interview Revision
```

> **Master-roadmap principle:** SQL begins modestly, grows alongside backend development, and becomes a maintained placement skill rather than a one-time course.
