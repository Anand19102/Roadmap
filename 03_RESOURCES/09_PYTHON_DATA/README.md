# 🐍 09 — PYTHON / DATA RESOURCE MAP

> **Purpose:** Secondary technical track for Python, NumPy, Pandas, data analysis and eventually Power BI.
>
> **Priority:** 🟡 Secondary
>
> **Strategic rule:** This track must **not compete with Java + DSA + Backend** during the early stages of preparation.
>
> Python/Data will be introduced after meaningful progress has been made in the primary stack.

---

# 1. Strategic Role

The Python/Data track exists for three reasons:

1. Support the user's college/lab requirements.
2. Build a useful secondary technical skill.
3. Create an optional Data Analysis → Power BI project path.

It is **NOT** the primary placement stack.

### Primary stack

```text
Java
  ↓
DSA
  ↓
SQL
  ↓
Spring Boot
  ↓
Backend
  ↓
Docker / Cloud
  ↓
Projects
  ↓
Internship / Placement
```

### Secondary stack

```text
Python
  ↓
NumPy
  ↓
Pandas
  ↓
Data Cleaning
  ↓
Exploratory Data Analysis
  ↓
Visualization
  ↓
Power BI
  ↓
DAX
  ↓
Data Project
```

---

# 2. Python

## Primary Resource

### Python Official Documentation

Use the official Python documentation primarily as a **reference**, not as the main teaching course.

* Python Tutorial
* Built-in types
* Control flow
* Functions
* Data structures
* Modules
* Exceptions
* File handling
* Classes
* Standard library

Official documentation:

https://docs.python.org/3/

Python's official documentation currently includes the Tutorial, Library Reference, Language Reference and Python HOWTOs.

---

## Python Beginner Resource

### Python.org Beginner Resources

Use when a quick refresher is required.

https://www.python.org/about/gettingstarted/

Python's own beginner guidance is specifically intended to help newcomers get started with installation, editors and learning resources.

---

# 3. Python Topics We Actually Need

We do **not** need to become a Python specialist.

### Must know

* Variables
* Data types
* Operators
* `if / elif / else`
* `for`
* `while`
* Functions
* Lists
* Tuples
* Sets
* Dictionaries
* Strings
* List/dictionary comprehensions
* Slicing
* Basic exception handling
* File handling
* Modules
* Basic OOP
* Virtual environments
* `pip`
* Jupyter notebooks

### Understand/use

* Lambda functions
* `map`
* `filter`
* `zip`
* `enumerate`
* `collections`
* basic standard library usage

### Lower priority

* Advanced decorators
* Metaclasses
* advanced descriptors
* Python internals
* advanced asynchronous programming

These are **not placement priorities** for the intended backend path.

---

# 4. NumPy

## Primary Resources

### Official NumPy User Guide

https://numpy.org/doc/stable/user/

### NumPy Learn

https://numpy.org/learn/

The official NumPy learning resources cover the NumPy quickstart, array creation, indexing, data types, broadcasting, copies/views, universal functions and related fundamentals.

---

## NumPy Topics

### 🟠 Strong Understanding

* `ndarray`
* Array creation
* Shape
* Dimensions
* Indexing
* Slicing
* Reshaping
* Data types
* Vectorized operations
* Broadcasting
* Aggregation
* Boolean masking

### 🟡 Learn / Use

* Random module
* Basic linear algebra
* Basic statistical operations
* Saving/loading arrays

### 🟢 Skim

* Advanced NumPy internals
* C API
* advanced interoperability
* performance internals

The official documentation itself separates beginner fundamentals from advanced developer-oriented material, so the roadmap should follow that distinction.

---

# 5. Pandas

## Primary Resource

### Official Pandas Documentation

https://pandas.pydata.org/docs/

Pandas should become the **main practical Python data-analysis library**.

### Topics

#### 🟠 Strong Understanding

* Series
* DataFrame
* Creating/loading data
* `read_csv`
* inspecting data
* selecting columns
* filtering rows
* indexing
* missing values
* sorting
* grouping
* aggregation
* merging
* joining
* concatenation

#### 🟡 Learn / Use

* `pivot_table`
* reshaping
* datetime handling
* categorical data
* exporting data
* basic performance considerations

#### 🟢 Skim

* highly specialized internals
* advanced extension APIs
* obscure performance features

---

# 6. Data Analysis

The goal is not to memorize Pandas functions.

The goal is to understand:

```text
Question
   ↓
Acquire data
   ↓
Inspect
   ↓
Clean
   ↓
Transform
   ↓
Explore
   ↓
Analyze
   ↓
Visualize
   ↓
Communicate insight
```

### 🟠 Strong Understanding

* Data cleaning
* Missing-value handling
* Outlier identification
* Duplicate handling
* Data type correction
* Aggregation
* Grouping
* Correlation
* Basic descriptive statistics
* EDA
* Asking useful analytical questions

### 🟡 Learn / Use

* Matplotlib
* Seaborn
* basic chart selection
* distributions
* relationships
* categorical comparisons

---

# 7. Notebook Workflow

For data projects:

```text
01_problem_statement.ipynb
02_data_loading.ipynb
03_data_cleaning.ipynb
04_eda.ipynb
05_analysis.ipynb
06_visualization.ipynb
07_conclusions.ipynb
```

Do not create notebooks that are merely collections of copied tutorial cells.

Every project must answer an actual question.

---

# 8. Relationship With Power BI

The eventual pipeline is:

```text
Python
 ↓
NumPy / Pandas
 ↓
Data Cleaning + Analysis
 ↓
CSV / Database
 ↓
Power BI
 ↓
Dashboard
 ↓
Business Insights
```

Python/Data is therefore a **supporting project ecosystem**, not a competing career track.

---

# 9. What NOT to Learn

Do not allow this folder to expand indefinitely.

Not currently required:

* Machine learning
* Deep learning
* TensorFlow
* PyTorch
* advanced statistics
* advanced Python internals
* data engineering
* Spark
* Airflow

These may become future options, but they are outside the current roadmap unless career direction changes.

---

# 10. Resource Usage Rule

**Official documentation = reference**

**Practical course/tutorial = learning**

**Project = mastery**

The order is:

```text
Learn
 ↓
Small exercises
 ↓
Use on dataset
 ↓
Build project
 ↓
Explain decisions
```

Never:

```text
Watch course
 ↓
Declare Python finished
```

---

# 11. Final Resource Priority

| Resource                       | Priority               |
| ------------------------------ | ---------------------- |
| Python official docs           | 🟠 Reference           |
| Python beginner material       | 🟡                     |
| NumPy official                 | 🟡                     |
| Pandas official                | 🟠                     |
| Matplotlib                     | 🟡                     |
| Seaborn                        | 🟢/🟡                  |
| Real datasets                  | 🟠                     |
| Jupyter                        | 🟠                     |
| Random advanced Python courses | 🟢 Avoid unless needed |

---

## Bottom Line

Python/Data is deliberately **secondary**.

The roadmap should introduce it only after the primary Java/DSA/backend foundation is sufficiently established.

Its purpose is to give the user:

> **practical Python + data analysis + Power BI competence**

without allowing it to derail:

> **Java + DSA + backend + internship/placement preparation.**
