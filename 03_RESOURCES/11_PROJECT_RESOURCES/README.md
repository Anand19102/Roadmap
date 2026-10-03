# 🏗️ 11 — PROJECT RESOURCE MAP

> **Purpose:** Central resource map for building progressively stronger projects.
>
> **Core philosophy:** Projects are not an afterthought. They are where learning becomes demonstrable engineering ability.

---

# 1. Project Hierarchy

Projects will progress through:

```text
Micro Projects
      ↓
Java Projects
      ↓
Backend Projects
      ↓
Full-Stack Projects
      ↓
Serious Portfolio Project
      ↓
Optional Data / Power BI Project
```

---

# 2. Project Learning Sources

## A. Primary Backend Resource

### Telusko Java + Spring Boot Course

Use the supplied Telusko course as the primary structured learning source.

Relevant project/backend sections include:

* Building a Project
* REST using Spring Boot
* Spring Data JPA
* Project using Spring Boot MVC
* Spring Security
* JWT/OAuth2
* Docker
* Cloud Deployment
* Microservices

The supplied syllabus contains dedicated project, REST, JPA, security, Docker, cloud, Kubernetes, CI/CD and microservice sections.

---

# 3. Spring Official Resources

### Spring Boot Documentation

https://docs.spring.io/spring-boot/documentation/

Use for:

* API/reference clarification
* configuration
* production features
* web
* data
* containerization
* deployment

Spring's documentation currently organizes material into first steps, web, data, messaging, container images, production and advanced topics.

### Spring Guides

https://spring.io/guides

Particularly useful for learning how official Spring projects are structured.

The official Getting Started guide demonstrates creating a Spring Boot application through Spring Initializr and building a simple web application.

### Spring Tutorials

https://spring.io/guides/tutorials/

Use for deeper in-context enterprise application topics.

---

# 4. Docker

### Official Docker Get Started

https://docs.docker.com/get-started/

Use when Docker becomes part of the project.

Important concepts:

* Images
* Containers
* Dockerfile
* Ports
* Volumes
* Networks
* Docker Compose
* Containerizing Spring Boot
* PostgreSQL containers

Docker's official getting-started material includes containerizing applications and running application stacks.

---

# 5. Cloud

### AWS Getting Started

https://aws.amazon.com/getting-started/

Use when the project reaches deployment.

Relevant concepts:

* IAM
* EC2/ECS
* RDS
* ECR
* networking fundamentals
* deployment
* cloud architecture

AWS provides beginner onboarding and tutorials for building applications on AWS.

---

# 6. Git / GitHub

Use Git as part of **every serious project**.

Primary reference:

https://git-scm.com/doc

Required workflow:

```text
Create repository
 ↓
README
 ↓
Meaningful commits
 ↓
Branches when appropriate
 ↓
Pull/merge discipline
 ↓
Issues
 ↓
Tags/releases when useful
```

Never upload a project only after finishing it.

Git history should demonstrate actual development.

---

# 7. Project Types

## Level 1 — Micro Projects

Purpose:

> Learn a concept through implementation.

Examples:

* Java calculator
* Student management CLI
* Banking CLI
* File-processing utility
* Simple JDBC program
* Small REST endpoint

Characteristics:

* small
* 1–3 concepts
* short duration
* disposable
* not necessarily resume-worthy

---

# 8. Level 2 — Java Projects

Purpose:

> Combine multiple Java concepts.

Examples:

* Library Management System
* Expense Tracker
* Inventory Manager
* Student Management System

Potential concepts:

* OOP
* collections
* exceptions
* file handling
* JDBC
* SQL

---

# 9. Level 3 — Backend Projects

Purpose:

> Demonstrate actual backend engineering.

Typical architecture:

```text
Client
  ↓
REST API
  ↓
Controller
  ↓
Service
  ↓
Repository
  ↓
Database
```

Potential features:

* CRUD
* validation
* pagination
* filtering
* authentication
* authorization
* database relationships
* exception handling
* logging
* testing

---

# 10. Level 4 — Full-Stack

Frontend becomes relevant here.

Likely stack:

```text
React
 ↓
REST API
 ↓
Spring Boot
 ↓
PostgreSQL
```

Frontend is introduced only after backend fundamentals are sufficiently strong.

The objective is **not** to become a frontend specialist.

The objective is:

> be capable of building and demonstrating a complete application.

---

# 11. Level 5 — Serious Portfolio Project

This is the most important project category.

The project must demonstrate:

* Java
* Spring Boot
* REST
* SQL
* JPA/Hibernate
* authentication
* authorization
* validation
* testing
* Docker
* deployment
* Git/GitHub
* clean architecture
* documentation

Potential later additions:

* caching
* messaging
* asynchronous processing
* observability
* microservices
* cloud services

---

# 12. Serious Project Development Stages

Every major project should follow:

```text
1. Problem discovery
        ↓
2. Requirements
        ↓
3. Feature specification
        ↓
4. Architecture
        ↓
5. Database design
        ↓
6. API design
        ↓
7. Project setup
        ↓
8. MVP
        ↓
9. Feature development
        ↓
10. Testing
        ↓
11. Security
        ↓
12. Refactoring
        ↓
13. Dockerization
        ↓
14. Deployment
        ↓
15. Documentation
        ↓
16. Resume integration
        ↓
17. Interview preparation
```

---

# 13. No-Tutorial-Copying Rule

Tutorials may be used for:

* understanding
* syntax
* architecture
* unfamiliar APIs
* debugging

They may NOT become the project itself.

Correct workflow:

```text
Learn concept
 ↓
Close tutorial
 ↓
Design your own implementation
 ↓
Build
 ↓
Get stuck
 ↓
Research specific problem
 ↓
Implement
 ↓
Explain why your solution works
```

---

# 14. Project Resource Order

The project should use resources according to the current learning stage.

Example:

```text
Learn REST
 ↓
Build tiny REST API
 ↓
Learn JPA
 ↓
Add database
 ↓
Learn Security
 ↓
Add authentication
 ↓
Learn Docker
 ↓
Containerize
 ↓
Learn deployment
 ↓
Deploy
```

Never wait until the end of the entire roadmap to build projects.

---

# 15. Data / Power BI Project Resources

Python/Data project:

```text
Python
 ↓
Pandas
 ↓
Dataset
 ↓
Cleaning
 ↓
EDA
 ↓
Visualization
 ↓
Insights
```

Power BI project:

```text
Dataset
 ↓
Power Query
 ↓
Data Model
 ↓
DAX
 ↓
Dashboard
 ↓
Business Insights
```

These belong in:

* `11_PROJECTS/06_PYTHON_DATA_PROJECTS`
* `11_PROJECTS/07_POWERBI_PROJECTS`

---

# 16. Project Documentation

Every serious project should contain:

```text
README.md
architecture.md
api-documentation.md
database-design.md
setup.md
testing.md
deployment.md
```

At minimum, README must explain:

* Problem
* Solution
* Features
* Tech stack
* Architecture
* Database
* API
* Setup
* Screenshots/demo
* Deployment
* Future improvements

---

# 17. Project Resources Rule

Resources should support **building**, not replace building.

The strongest evidence of learning is:

```text
Working project
+
Git history
+
Good README
+
Architecture explanation
+
Ability to defend technical decisions
```

---

# Final Principle

The project folder exists to answer:

> **"Can I actually build something with what I learned?"**

Not:

> **"How many tutorials have I completed?"**
