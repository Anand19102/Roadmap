# 🖥️ CORE CS SEQUENCE

## OOP → DBMS → Computer Networks → Operating Systems → Software Engineering → System Design

> **Master-roadmap file**
>
> Core CS is not a separate giant course that begins after all programming is finished.
>
> Each subject enters when it becomes relevant to the primary stack and is then repeatedly revised for internship and placement interviews.

---

# 1. CORE CS OBJECTIVE

The objective is to be able to answer interview questions such as:

* Why does this Java code behave this way?
* What happens when an API request reaches a server?
* How does a database execute a query?
* Why does indexing improve some queries?
* What happens during a transaction?
* What is a process vs thread?
* What happens when multiple threads access shared state?
* What happens when a client connects to a server?
* What happens at the TCP/HTTP level?
* How would you design a scalable backend?

---

# 2. CORE CS ORDER

The master sequence is:

```text
JAVA OOP
    ↓
DBMS + SQL
    ↓
COMPUTER NETWORKS
    ↓
OPERATING SYSTEMS
    ↓
SOFTWARE ENGINEERING
    ↓
SYSTEM DESIGN
```

But they overlap.

```text
Java
 └── OOP ────────────────┐
                         ↓
SQL ───────► DBMS ─────► Backend
                         ↓
CN ─────────────────────► APIs
                         ↓
OS ───────────────► Concurrency / Systems
                         ↓
Software Engineering ───► Projects
                         ↓
System Design ──────────► Distributed Backend
```

---

# 3. MASTERY SYSTEM

### 🔴 MASTER

Must answer interview questions clearly and explain mechanisms.

### 🟠 STRONG UNDERSTANDING

Must understand architecture and common interview questions.

### 🟡 LEARN / USE

Enough for practical engineering and basic interview questions.

### 🟢 SKIM

Know the idea; don't spend disproportionate time.

### ⚪ DEFER

Return later when the relevant career stage arrives.

---

# 4. SUBJECT 1 — OOP

## Why first?

Because OOP is simultaneously:

* Java foundation
* interview subject
* backend foundation
* project architecture foundation

---

# 5. OOP CORE TOPICS

### 🔴 MASTER

* class
* object
* encapsulation
* inheritance
* polymorphism
* abstraction
* interfaces
* method overloading
* method overriding
* constructors
* access modifiers
* `this`
* `super`
* static
* final
* dynamic method dispatch
* upcasting
* downcasting

Telusko's Core Java syllabus explicitly covers these areas.

---

# 6. OOP INTERVIEW TOPICS

Must eventually be able to explain:

* class vs object
* abstraction vs encapsulation
* inheritance
* composition vs inheritance
* overloading vs overriding
* interface vs abstract class
* static vs instance
* final
* polymorphism
* runtime dispatch
* `equals()`
* `hashCode()`
* `toString()`
* object references
* upcasting/downcasting

### Priority

🔴

---

# 7. SUBJECT 2 — DBMS

DBMS becomes active alongside SQL and backend.

---

# 8. DATABASE FUNDAMENTALS

### 🔴 MASTER

Learn:

* database
* DBMS
* relational model
* tables
* rows
* columns
* keys
* primary key
* foreign key
* constraints
* relationships

---

# 9. SQL + DBMS INTEGRATION

The SQL roadmap contains:

```text
SQL fundamentals
 ↓
Filtering/sorting
 ↓
Aggregations
 ↓
Joins
 ↓
Subqueries
 ↓
CTEs
 ↓
Window functions
 ↓
Database concepts
 ↓
Normalization
 ↓
Indexing
 ↓
Transactions
 ↓
Query optimization
```

SQL itself is maintained in:

`08_SQL_DATABASES/`

---

# 10. NORMALIZATION

### 🔴

Understand:

* redundancy
* update anomalies
* functional dependencies at practical level
* 1NF
* 2NF
* 3NF
* BCNF conceptually

Do not memorize normalization as meaningless definitions.

Understand **why decomposition is performed**.

---

# 11. INDEXING

### 🔴

Understand:

* why indexes exist
* lookup improvement
* trade-offs
* write overhead
* index selection
* basic B-tree/B+ tree concepts

---

# 12. TRANSACTIONS

### 🔴

Master:

* transaction
* ACID
* atomicity
* consistency
* isolation
* durability

Understand:

* commit
* rollback
* concurrency issues
* isolation-level concept

---

# 13. QUERY OPTIMIZATION

### 🟠

Understand:

* indexes
* query execution idea
* joins
* filtering
* avoiding unnecessary work
* why a query may be slow

Do not turn this into database-engine internals specialization.

---

# 14. SUBJECT 3 — COMPUTER NETWORKS

CN becomes increasingly important when backend/API development starts.

---

# 15. NETWORK FUNDAMENTALS

### 🔴

Learn:

* network basics
* client/server
* packets
* protocols
* IP
* ports
* sockets
* process-to-process communication

---

# 16. NETWORK MODELS

### 🟠 → 🔴

Understand:

* OSI model
* TCP/IP model
* layers
* responsibilities
* encapsulation

You should be able to explain **why layers exist**, not merely list them.

---

# 17. TRANSPORT LAYER

### 🔴

Master:

* TCP
* UDP
* ports
* process-to-process communication
* reliability
* flow control
* congestion concepts
* connection establishment
* connection termination

---

# 18. SOCKET PROGRAMMING

### 🔴 practical understanding

Know:

* socket
* bind
* listen
* accept
* connect
* send/receive
* client/server sequence
* TCP vs UDP
* concurrent clients
* basic server architecture

This directly supports backend/networking understanding.

---

# 19. APPLICATION LAYER

### 🔴

Focus on:

* HTTP
* HTTPS
* DNS
* client/server communication
* request/response
* methods
* status codes
* headers
* cookies
* basic authentication concepts

---

# 20. HTTP → SPRING BOOT CONNECTION

The conceptual chain must become:

```text
Browser/client
 ↓
HTTP request
 ↓
Network
 ↓
Server
 ↓
Spring Boot
 ↓
Controller
 ↓
Service
 ↓
Repository
 ↓
Database
 ↓
HTTP response
```

This connection is much more valuable than learning CN in isolation.

---

# 21. SUBJECT 4 — OPERATING SYSTEMS

OS is introduced after Java foundations and as concurrency/backend maturity grows.

---

# 22. PROCESSES

### 🔴

Understand:

* process
* process state
* process creation
* context switching
* process scheduling concept

---

# 23. THREADS

### 🔴

Connect OS threads to Java:

```text
OS thread concepts
        ↓
Java Thread
        ↓
Runnable
        ↓
Concurrency
```

Telusko introduces:

* Threads
* Multiple Threads
* Thread Priority and Sleep
* Runnable vs Thread
* Race Condition
* Thread States

These are therefore revisited from an OS/interview perspective.

---

# 24. CPU SCHEDULING

### 🟠

Know:

* scheduling
* FCFS
* SJF
* Round Robin
* priority scheduling
* waiting time
* turnaround time

Focus on interview understanding rather than excessive numerical drills unless college coursework requires them.

---

# 25. SYNCHRONIZATION

### 🔴

Understand:

* race condition
* critical section
* mutex/lock
* semaphore
* synchronization
* deadlock

---

# 26. DEADLOCK

### 🔴

Know:

* four necessary conditions
* prevention
* avoidance concept
* detection concept

Do not overcomplicate unless an interview demands it.

---

# 27. MEMORY MANAGEMENT

### 🟠

Understand:

* memory allocation
* virtual memory
* paging
* segmentation
* page faults
* basic page replacement concepts

---

# 28. FILE SYSTEMS

### 🟡 → 🟠

Understand:

* files
* directories
* file systems
* permissions
* storage concepts

---

# 29. OS INTERVIEW PRIORITY

Highest:

🔴

* process vs thread
* context switching
* scheduling basics
* synchronization
* race conditions
* deadlock
* memory/virtual memory basics

Lower:

🟡

* obscure OS implementation details

---

# 30. SUBJECT 5 — SOFTWARE ENGINEERING

This runs primarily through project development.

---

# 31. SOFTWARE DEVELOPMENT LIFE CYCLE

### 🟠

Understand:

* requirements
* design
* implementation
* testing
* deployment
* maintenance

---

# 32. VERSION CONTROL

### 🔴 practical

Git/GitHub:

* branch
* commit
* pull request
* merge
* conflict
* repository hygiene

---

# 33. CODE QUALITY

### 🔴 practical

Projects must demonstrate:

* readable naming
* modularity
* meaningful methods
* separation of concerns
* error handling
* documentation
* testing
* maintainability

---

# 34. TESTING

### 🟠

Understand:

* unit testing
* integration testing
* test cases
* regression
* mocks/stubs concept

JUnit5 becomes the Java implementation vehicle.

---

# 35. DESIGN PRINCIPLES

### 🟠

Learn:

* DRY
* KISS
* separation of concerns
* cohesion
* coupling
* SOLID

### Important

Do not memorize SOLID definitions without being able to recognize them in code.

---

# 36. SUBJECT 6 — SYSTEM DESIGN

System design comes **late**, not at the beginning.

Prerequisites:

```text
Java
+
Backend
+
SQL
+
CN
+
OS
+
Projects
+
Docker/deployment
```

---

# 37. SYSTEM DESIGN FOUNDATION

### 🟠

Learn:

* requirements
* functional requirements
* non-functional requirements
* scalability
* availability
* reliability
* latency
* throughput
* consistency

---

# 38. SYSTEM COMPONENTS

### 🔴 eventually

Understand:

* load balancer
* application server
* database
* cache
* message queue
* object storage
* CDN
* API gateway

---

# 39. DATABASE SCALING

### 🟠

Understand:

* replication
* partitioning/sharding
* read replicas
* indexing
* caching

---

# 40. CACHING

### 🟠

Understand:

* cache-aside
* TTL
* invalidation
* cache hit/miss
* consistency trade-offs

---

# 41. MESSAGING

### 🟠

Understand:

* producer
* consumer
* queue
* asynchronous processing
* retry
* failure handling

---

# 42. DISTRIBUTED SYSTEMS

### 🟠 → 🔴 later

Learn progressively:

* distributed communication
* replication
* partitioning
* consistency
* availability
* fault tolerance
* retries
* idempotency
* observability

---

# 43. CORE CS TIMING

## Early Java phase

Primary:

```text
OOP
```

Secondary:

```text
Basic OS awareness
```

---

## Java + DSA phase

Continue:

```text
OOP revision
+
DBMS basics
+
SQL
```

---

## Backend phase

Increase:

```text
DBMS
+
CN
+
OS concurrency
```

---

## Serious project phase

Add:

```text
Software Engineering
+
Testing
+
Design principles
```

---

## Advanced backend phase

Introduce:

```text
System Design
+
Distributed Systems
+
Cloud architecture
```

---

# 44. CORE CS REVISION MODEL

Each subject gets:

### First pass

Understand concepts.

### Second pass

Create concise notes.

### Third pass

Interview questions.

### Fourth pass

Active recall.

### Fifth pass

Mixed mock interview revision.

---

# 45. CORE CS QUESTION STANDARD

For every major concept, eventually be able to answer:

### Definition

> What is it?

### Why

> Why does it exist?

### Mechanism

> How does it work?

### Example

> Where would you use it?

### Comparison

> How is it different from X?

### Trade-off

> What are its advantages/disadvantages?

### Interview application

> What problem does it solve?

---

# 46. CORE CS PRIORITY

## 🔴 Highest priority

### OOP

* core principles
* Java implementation
* interview questions

### DBMS

* SQL
* keys
* normalization
* indexing
* transactions
* ACID

### CN

* TCP/UDP
* HTTP/HTTPS
* DNS
* ports
* sockets
* client/server

### OS

* process/thread
* scheduling
* synchronization
* deadlock
* memory

---

## 🟠 Strong

* Software Engineering
* testing
* SOLID
* system design fundamentals

---

## 🟡 Later

* deeper distributed systems
* advanced cloud architecture
* advanced infrastructure

---

# 47. CORE CS + PROJECT INTEGRATION

Never study everything only theoretically.

Example:

### You build a REST API

Immediately connect:

```text
HTTP
 ↓
CN

Controller
 ↓
OOP / Spring

Database
 ↓
DBMS / SQL

Concurrent requests
 ↓
OS / Threads

Authentication
 ↓
Security

Deployment
 ↓
Cloud / Networking
```

This creates much stronger retention.

---

# 48. INTERNSHIP READINESS TARGET

Before the major internship interview window, the target is:

### OOP

🔴

### DBMS

🟠 → 🔴

### SQL

🔴

### CN fundamentals

🟠 → 🔴

### OS fundamentals

🟠

### Git/software engineering

🟠

You do **not** need to be a system-design specialist yet.

---

# 49. PLACEMENT READINESS TARGET

Before major placement preparation:

```text
OOP          🔴
DBMS         🔴
SQL          🔴
CN           🔴
OS           🔴
SE           🟠
System Design 🟠
```

Then continuous interview revision begins.

---

# 50. FINAL CORE CS ARCHITECTURE

```text
JAVA
  ↓
OOP
  ↓
SQL
  ↓
DBMS
  ↓
SPRING BOOT / BACKEND
  ↓
COMPUTER NETWORKS
  ↓
OPERATING SYSTEMS
  ↓
SOFTWARE ENGINEERING
  ↓
SYSTEM DESIGN
  ↓
DISTRIBUTED SYSTEMS
```

The subjects are **not isolated**.

They form one engineering mental model.

---

# 51. GOLDEN RULE

> **Learn Core CS when the rest of the roadmap gives you something concrete to attach it to.**

OOP makes sense through Java.

DBMS makes sense through SQL and backend.

CN makes sense through APIs and socket programming.

OS makes sense through processes, threads and concurrency.

System Design makes sense after you have actually built and deployed systems.

---

**END OF `07_CORE_CS_SEQUENCE.md`**
