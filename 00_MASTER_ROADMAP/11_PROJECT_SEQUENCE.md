# 11 — PROJECT SEQUENCE

> **Purpose:** Turn learning into demonstrable engineering ability.
>
> The roadmap does **not** follow the pattern:
>
> `Learn everything → copy a tutorial project → put it on GitHub → repeat.`
>
> Instead:
>
> `Learn → build small → understand → modify → design → build independently → document → deploy → explain → iterate.`

---

# 1. Project Philosophy

Projects exist to prove that knowledge can be converted into working software.

A project must therefore progressively demonstrate:

* programming ability
* problem solving
* software design
* Git/GitHub usage
* SQL/database skills
* API development
* testing
* debugging
* code quality
* deployment
* documentation
* communication

---

# 2. Project Levels

```text
LEVEL 0
Micro exercises
       ↓
LEVEL 1
Small Java projects
       ↓
LEVEL 2
Database-backed applications
       ↓
LEVEL 3
Spring Boot REST projects
       ↓
LEVEL 4
Full-stack application
       ↓
LEVEL 5
Serious backend portfolio project
       ↓
LEVEL 6
Production-oriented enhancement
```

Python/Data projects run as a separate secondary branch.

---

# 3. LEVEL 0 — Micro Projects

Examples:

* console utilities
* small Java programs
* file-processing programs
* simple CRUD logic
* small algorithmic utilities

### Purpose

Build confidence.

### Requirements

* finish independently
* understand every line
* modify the program
* debug your own mistakes

### Classification

🟢 project depth, but **important for habit formation**

Do not polish these endlessly.

---

# 4. LEVEL 1 — Small Java Projects

These come after sufficient Java fundamentals.

Possible categories:

* console management system
* expense tracker
* student/course manager
* library manager
* simple text-based utility

### Required Java concepts

* classes
* objects
* methods
* collections
* exception handling
* file handling where appropriate

### Goal

Move from:

> "I can solve coding exercises."

to:

> "I can organise a small program."

---

# 5. LEVEL 2 — Database-Backed Projects

Once SQL fundamentals are established, projects should introduce persistent data.

Architecture:

```text
Application
     ↓
Java logic
     ↓
SQL
     ↓
Relational database
```

Learn:

* schema design
* tables
* keys
* relationships
* CRUD
* SQL queries
* validation
* error handling

---

# 6. LEVEL 3 — Spring Boot REST Projects

After sufficient:

* Java
* OOP
* collections
* exceptions
* SQL
* basic backend concepts

introduce:

```text
Spring
 ↓
Spring Boot
 ↓
REST
 ↓
Database
```

Project capabilities should progressively include:

* REST endpoints
* request/response handling
* DTOs
* validation
* service layer
* repository layer
* database integration
* exception handling

---

# 7. Project Architecture Progression

Early:

```text
Controller
 ↓
Service
 ↓
Repository
 ↓
Database
```

Later introduce:

* DTOs
* validation
* authentication
* authorisation
* testing
* logging
* configuration management
* caching where appropriate

Do not add architecture merely for decoration.

Every layer should solve an actual problem.

---

# 8. LEVEL 4 — Full-Stack Project

Frontend is deliberately introduced **after backend fundamentals exist**.

The intended relationship is:

```text
Frontend
   ↓
REST API
   ↓
Spring Boot
   ↓
Service
   ↓
Repository
   ↓
Database
```

Frontend should initially focus on:

* HTML/CSS fundamentals
* JavaScript fundamentals
* HTTP/API interaction
* basic React
* component structure
* state
* forms
* API calls

The goal is **backend-first full-stack competence**, not becoming a specialist frontend developer.

---

# 9. LEVEL 5 — Serious Portfolio Backend Project

This is the major project.

It should be substantially more sophisticated than tutorial projects.

Potential capabilities:

* authentication
* authorisation
* role-based access
* relational database
* proper schema design
* REST API
* validation
* pagination
* filtering
* sorting
* error handling
* testing
* logging
* documentation
* Docker
* deployment
* monitoring basics
* performance considerations

Later enhancements may include:

* caching
* asynchronous processing
* messaging
* service separation
* cloud deployment
* scalability considerations

---

# 10. Serious Project Development Stages

Every serious project follows these stages.

## Stage 1 — Problem Discovery

Define:

* problem
* target users
* use cases
* constraints
* assumptions

---

## Stage 2 — Requirements

Write:

* functional requirements
* non-functional requirements
* user stories
* edge cases

---

## Stage 3 — System Design

Determine:

* architecture
* components
* API boundaries
* database schema
* data flow

---

## Stage 4 — Technology Selection

Only choose technologies that serve the requirements.

Avoid:

> "This technology looks impressive, so I'll add it."

---

## Stage 5 — MVP

Build the smallest genuinely usable version.

```text
Requirement
 ↓
Implementation
 ↓
Test
 ↓
Commit
```

---

## Stage 6 — Database

Design:

* tables
* keys
* relationships
* constraints
* indexes where appropriate

---

## Stage 7 — Backend

Implement:

* controllers
* services
* repositories
* DTOs
* validation
* exception handling

---

## Stage 8 — Testing

Introduce:

* unit tests
* integration tests
* API testing
* edge-case testing

---

## Stage 9 — Frontend

Only after the API is stable enough.

Build:

* UI
* forms
* API integration
* loading/error states
* basic usability

---

## Stage 10 — Security

Where relevant:

* authentication
* authorisation
* password handling
* token/session handling
* input validation
* secure configuration

---

## Stage 11 — Docker

Containerise the application when the project architecture is mature enough.

---

## Stage 12 — Deployment

Deploy the project.

Document:

* environment
* configuration
* database
* deployment procedure
* known limitations

---

## Stage 13 — Performance / Reliability

Investigate:

* inefficient queries
* unnecessary API calls
* caching opportunities
* concurrency issues
* failure cases

---

## Stage 14 — Documentation

README must explain:

* problem
* features
* architecture
* tech stack
* setup
* API
* database
* screenshots
* deployment
* limitations
* future improvements

---

## Stage 15 — Resume Conversion

Extract:

* measurable outcomes
* technical decisions
* engineering challenges
* scale where genuinely measurable
* performance improvements
* deployment details

---

# 11. The No-Tutorial-Copying Rule

Tutorials are allowed.

**Tutorial dependency is not.**

Use:

```text
Watch
 ↓
Understand
 ↓
Close tutorial
 ↓
Rebuild
 ↓
Modify
 ↓
Add your own feature
 ↓
Debug independently
 ↓
Document
```

If you cannot explain the project without the tutorial, the project is not yet portfolio-ready.

---

# 12. Tutorial Usage by Project Level

### Level 0

Tutorial/reference:

🟢 acceptable.

### Level 1

Tutorial:

🟡 reference only.

### Level 2

Tutorial:

🟡 use selectively.

### Level 3

Tutorial:

🟢/🟡 only for unfamiliar framework concepts.

### Level 4

Mostly independent.

### Level 5

The architecture and implementation should be primarily yours.

---

# 13. Project Git Workflow

Every meaningful project should use Git.

Basic progression:

```text
init
 ↓
meaningful commits
 ↓
branches when appropriate
 ↓
pull requests where useful
 ↓
README
 ↓
issues/tasks
 ↓
tag/release
```

Commit messages should describe actual changes.

---

# 14. Project Quality Checklist

Before calling a project complete:

### Functionality

* [ ] Core features work
* [ ] Edge cases considered
* [ ] Errors handled

### Code

* [ ] Understandable
* [ ] Modular
* [ ] No unnecessary duplication
* [ ] Meaningful names
* [ ] Appropriate abstractions

### Database

* [ ] Schema makes sense
* [ ] Relationships correct
* [ ] Queries reviewed

### Backend

* [ ] API endpoints documented
* [ ] Validation present
* [ ] Exceptions handled
* [ ] Appropriate HTTP responses

### Testing

* [ ] Important behaviour tested
* [ ] Failure cases tested

### GitHub

* [ ] Clean repository
* [ ] README
* [ ] Setup instructions
* [ ] Screenshots where useful

### Deployment

* [ ] Application deployable
* [ ] Configuration documented

### Interview

You can explain:

* why you built it
* architecture
* database design
* difficult problem
* trade-offs
* bugs
* improvements
* what you would change at scale

---

# 15. Python/Data/Power BI Project Branch

This branch begins later.

The project progression is:

```text
Python
 ↓
Pandas
 ↓
Data cleaning
 ↓
Exploratory analysis
 ↓
Visualisation
 ↓
Power BI
 ↓
Dashboard
 ↓
Business insights
```

The project should answer an actual question rather than merely display charts.

---

# 16. Portfolio Project Portfolio

The final portfolio should not contain ten mediocre projects.

Target structure:

```text
Several small learning projects
        +
A few solid technical projects
        +
1 serious backend portfolio project
        +
1 full-stack project where useful
        +
1 Python/Data/Power BI project
```

Quality > quantity.

---

# 17. Internship Project Strategy

Before internship season, prioritise projects that demonstrate:

* Java
* Spring Boot
* SQL
* REST APIs
* Git/GitHub
* testing
* database design

The serious portfolio project should be sufficiently mature to discuss during technical interviews.

---

# 18. Placement Project Strategy

For placement interviews, every major project must become an interview asset.

Prepare:

### 30-second explanation

What it is.

### 2-minute explanation

Problem + architecture + contribution.

### 5–10-minute explanation

Detailed architecture, database, technical decisions and challenges.

### Deep-dive preparation

Be ready for:

* Why Java?
* Why Spring Boot?
* Why this database?
* Why this schema?
* Why this architecture?
* What happens when a request arrives?
* How authentication works
* How errors are handled
* How the application scales
* What you would change

---

# 19. Project Timing

Projects are introduced progressively rather than all at once.

```text
Java fundamentals
 ↓
Micro projects
 ↓
Java project
 ↓
SQL
 ↓
Database project
 ↓
Spring Boot
 ↓
REST project
 ↓
Backend project
 ↓
Frontend fundamentals
 ↓
Full-stack project
 ↓
Serious backend portfolio project
 ↓
Docker / deployment
 ↓
Cloud / scalability
```

Python/Data project:

```text
After primary-stack advancement
 ↓
Python
 ↓
Pandas
 ↓
Power BI
 ↓
Data project
```

---

# 20. Final Project Rule

> **Every project must increase your actual engineering ability.**

If a project adds only another technology name to the resume but does not improve:

* problem solving
* coding
* architecture
* databases
* APIs
* testing
* deployment
* communication

then it does not deserve significant roadmap time.

---

# 21. Project-to-Resume Pipeline

```text
Learn
 ↓
Build
 ↓
Debug
 ↓
Improve
 ↓
Deploy
 ↓
Document
 ↓
Measure
 ↓
Explain
 ↓
Resume bullet
 ↓
Interview story
```

The resume is therefore built **continuously**, not at the end of the entire roadmap.
