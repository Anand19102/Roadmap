# 📊 10 — POWER BI RESOURCE MAP

> **Purpose:** Secondary analytics / business intelligence track.
>
> **Priority:** 🟡 Secondary / later-stage
>
> **Target:** Practical Power BI competence + optional PL-300 certification + strong portfolio project.
>
> **Important:** Power BI should **not** be introduced during the early Java/DSA foundation period.

---

# 1. Strategic Position

Power BI belongs to the secondary track:

```text
Primary
Java → DSA → Spring Boot → Backend → Cloud
                 ↓
             Placements

Secondary
Python → Pandas → Data Analysis → Power BI
                                  ↓
                              Data Project
```

Power BI should become active when the primary stack has already reached a meaningful level.

---

# 2. Primary Official Resource

## Microsoft Learn — PL-300

Use Microsoft Learn as the authoritative resource for the certification syllabus.

https://learn.microsoft.com/credentials/certifications/resources/study-guides/pl-300

The current Microsoft PL-300 study guide identifies four major skill areas:

* Prepare the data — 25–30%
* Model the data — 25–30%
* Visualize and analyze the data — 25–30%
* Manage and secure Power BI — 15–20%

This structure should guide the eventual study sequence.

---

# 3. Power BI Learning Sequence

```text
Power BI interface
       ↓
Get data
       ↓
Power Query
       ↓
Data cleaning
       ↓
Data modeling
       ↓
Relationships
       ↓
DAX
       ↓
Visualizations
       ↓
Report design
       ↓
Analytics
       ↓
Publishing / workspaces
       ↓
Security
       ↓
PL-300 preparation
```

---

# 4. Power Query

### 🟠 Strong Understanding

* Connecting to data
* Importing CSV/Excel
* Transforming data
* Changing types
* Removing columns
* Filtering
* Splitting columns
* Replacing values
* Removing duplicates
* Handling nulls
* Merging queries
* Appending queries
* Basic query steps

Power Query should be learned **hands-on**.

Do not merely memorize menu locations.

---

# 5. Data Modeling

### 🔴 Master

* Tables
* Relationships
* Primary/foreign-key concepts
* Fact tables
* Dimension tables
* Star schema
* Relationship direction
* Cardinality
* Date tables

This is one of the most important conceptual areas.

---

# 6. DAX

### 🟠 Strong Understanding → eventually 🔴 Master

Initially learn:

* Measures
* Calculated columns
* Basic aggregation
* `SUM`
* `AVERAGE`
* `COUNT`
* `DISTINCTCOUNT`
* `CALCULATE`
* `FILTER`
* basic iterator concepts
* filter context
* row context

Eventually understand:

* context transition
* time intelligence
* common date calculations
* `ALL`
* `REMOVEFILTERS`
* `VALUES`
* `RELATED`
* `SUMX`
* `AVERAGEX`

Do not attempt to memorize every DAX function.

The objective is:

> understand how DAX evaluates expressions and know how to find the correct function when required.

---

# 7. Visualization

### 🟠 Strong Understanding

Learn when to use:

* Bar chart
* Column chart
* Line chart
* Area chart
* Scatter plot
* Table
* Matrix
* Cards
* KPI
* Slicer
* Maps when appropriate

Also learn:

* visual hierarchy
* filtering
* drill-down
* tooltips
* interactions
* report navigation
* dashboard storytelling

---

# 8. Report Design

The user should be able to answer:

> **What is the business question?**

before creating visuals.

Correct workflow:

```text
Business question
 ↓
Required metric
 ↓
Required data
 ↓
Model
 ↓
Measure
 ↓
Visual
 ↓
Insight
```

Not:

```text
Open Power BI
 ↓
Make random charts
```

---

# 9. Power BI Service

### 🟡 Learn / Use

* Workspaces
* Publishing
* Reports vs dashboards
* Sharing
* Refresh
* Basic permissions
* Basic security
* Row-level security

The current PL-300 framework explicitly includes managing and securing Power BI as a separate exam domain.

---

# 10. PL-300

PL-300 is an **optional certification**, not the central career objective.

Use it if:

* the college voucher is available,
* the timing is favorable,
* the certification can be completed without damaging the primary roadmap.

The current Microsoft study guide should always be checked before serious certification preparation because Microsoft updates exam objectives.

---

# 11. Certification Preparation

Near the certification period:

```text
Microsoft Learn
 ↓
Hands-on Power BI
 ↓
Official skills outline
 ↓
Practice assessment
 ↓
Weak-area revision
 ↓
Exam
```

Microsoft provides a practice assessment and official study resources.

---

# 12. Project Resource Strategy

The eventual Power BI project should use:

* a real dataset
* a defined business question
* cleaned data
* proper model
* calculated measures
* meaningful visuals
* written conclusions

The project belongs in:

`11_PROJECTS/07_POWERBI_PROJECTS`

---

# 13. What NOT to Overlearn

Do not spend excessive time on:

* obscure DAX functions
* advanced M language
* complex enterprise administration
* advanced Power Platform ecosystem
* Fabric-heavy material unless specifically needed
* obscure visualization tricks

---

# 14. Resource Priority

| Resource                           | Priority   |
| ---------------------------------- | ---------- |
| Microsoft Learn PL-300             | 🔴 Primary |
| Official Power BI documentation    | 🟠         |
| Hands-on datasets                  | 🔴         |
| Practice assessments               | 🟠         |
| Random YouTube tutorials           | 🟡         |
| Advanced Power Platform            | 🟢 Later   |
| Advanced enterprise administration | 🟢 Later   |

---

## Bottom Line

Power BI is a **secondary employability/certification/project skill**.

It should strengthen the profile rather than compete with the main:

> **Java + DSA + Backend + SQL + Core CS**

roadmap.
