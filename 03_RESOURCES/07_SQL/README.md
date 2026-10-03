# 🗄️ SQL & DATABASES — RESOURCE MAP

> **Purpose:** Central resource map for SQL, database concepts and SQL interview preparation.

---

# 🎯 ROLE IN THE ROADMAP

SQL is a CORE skill for the target backend path.

It connects:

Java
↓
Backend
↓
Database
↓
Spring Data / JPA
↓
Real projects
↓
Technical interviews

SQL therefore begins relatively early compared with Python / Power BI.

---

# 🥇 PRIMARY PRACTICE RESOURCE

## DataLemur

DataLemur is the main interview-practice resource.

Use it primarily for:

- SQL problem solving
- interview-style SQL
- joins
- aggregation
- subqueries
- CTEs
- window functions
- business-style questions

DataLemur currently provides SQL questions categorized by difficulty and
includes company-tagged interview questions. :contentReference[oaicite:4]{index=4}

---

# 🥈 SUPPORTING RESOURCES

## MySQL / PostgreSQL documentation

Use official database documentation when exact behaviour matters.

Do not read documentation cover-to-cover.

Use it as a reference.

---

## SQL Practice

Additional platforms may be used when required:

- HackerRank SQL
- LeetCode Database problems
- SQLBolt / similar interactive resources
- database documentation

These are supplementary.

They do NOT replace DataLemur as our main interview-oriented practice layer.

---

# 📚 SQL LEARNING ORDER

The roadmap should follow approximately:

## Stage 1 — Fundamentals

- SELECT
- FROM
- WHERE
- DISTINCT
- ORDER BY
- LIMIT
- aliases

↓

## Stage 2 — Filtering

- AND
- OR
- NOT
- IN
- BETWEEN
- LIKE
- NULL handling

↓

## Stage 3 — Aggregation

- COUNT
- SUM
- AVG
- MIN
- MAX
- GROUP BY
- HAVING

↓

## Stage 4 — Joins

- INNER JOIN
- LEFT JOIN
- RIGHT JOIN
- FULL JOIN concept
- SELF JOIN
- CROSS JOIN concept

↓

## Stage 5 — Subqueries

- scalar subqueries
- correlated subqueries
- EXISTS
- NOT EXISTS

↓

## Stage 6 — CTEs

- WITH
- multiple CTEs
- recursive CTE concept

↓

## Stage 7 — Window Functions

- OVER
- PARTITION BY
- ORDER BY
- ROW_NUMBER
- RANK
- DENSE_RANK
- LAG
- LEAD
- running totals
- moving calculations

↓

## Stage 8 — Database Concepts

- primary keys
- foreign keys
- constraints
- normalization
- indexes
- transactions
- ACID
- isolation
- locking
- query execution basics

↓

## Stage 9 — Backend SQL

Apply SQL to:

- Java
- JDBC
- Spring Boot
- JPA/Hibernate
- repositories
- transactions

---

# 🧠 WHAT TO MASTER

## HIGH PRIORITY

Master:

- SELECT
- WHERE
- GROUP BY
- HAVING
- JOINs
- aggregation
- subqueries
- CTEs
- window functions

These are extremely important for interview problems.

---

# 🟠 STRONG UNDERSTANDING

Strongly understand:

- indexes
- normalization
- transactions
- ACID
- isolation levels
- query execution
- database design

---

# 🟡 LEARN / USE

Learn enough to use:

- views
- stored procedures
- triggers
- advanced database-specific syntax

These are not early priorities.

---

# 🟢 SKIM

Skim:

- obscure vendor-specific features
- rarely-used administrative features
- database internals beyond interview relevance

---

# 🚫 DO NOT OVERLEARN

We are not trying to become:

> Database Administrators.

We are becoming:

> Java backend engineers who can work confidently with relational databases.

---

# 🧪 PRACTICE MODEL

For every SQL topic:

### 1. Learn syntax

↓

### 2. Write 3–5 tiny queries

↓

### 3. Solve easy problems

↓

### 4. Solve medium interview problems

↓

### 5. Record mistakes

↓

### 6. Re-solve without seeing the answer

↓

### 7. Use the concept in a backend project

---

# 📊 DIFFICULTY PROGRESSION

### Easy

Use to build syntax fluency.

### Medium

Main interview preparation level.

### Hard

Use selectively after fundamentals are strong.

DataLemur currently provides separate Easy, Medium and Hard SQL question
sets, making this progression practical. :contentReference[oaicite:5]{index=5}

---

# 🔗 PRIMARY RESOURCE

DataLemur SQL:

https://datalemur.com/sql-interview-questions

---

# 🔗 SECONDARY

LeetCode Database:

https://leetcode.com/problemset/database/

HackerRank SQL:

https://www.hackerrank.com/domains/sql

---

# GOLDEN RULE

> SQL should not be learned only for an aptitude-style exam.

The end goal is:

**Write SQL → understand what the database is doing → integrate it into backend
applications → explain it in interviews.**