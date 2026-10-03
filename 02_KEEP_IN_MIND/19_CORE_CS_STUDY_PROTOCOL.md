# 19 — Core CS Study Protocol

> **Purpose:** Build interview-ready Computer Science fundamentals without turning the roadmap into an academic-theory marathon.

---

# 1. Core CS Subjects

The roadmap primarily covers:

1. OOP
2. DBMS
3. Operating Systems
4. Computer Networks
5. Software Engineering
6. System Design

SQL is maintained separately because it is both a technical skill and a placement requirement.

---

# 2. Core CS Philosophy

Core CS should not be studied as isolated university theory.

The objective is:

> **Understand the concepts well enough to explain them, connect them to real software, and answer interview questions.**

For each subject:

**Concept → intuition → technical definition → example → implementation/use → interview questions → revision**

---

# 3. Priority

## 🔴 Master

Concepts that repeatedly matter for software-engineering interviews.

Examples:

### OOP

* class/object
* encapsulation
* abstraction
* inheritance
* polymorphism
* interfaces
* composition
* overriding/overloading
* access modifiers
* SOLID basics

### DBMS

* keys
* constraints
* normalization
* transactions
* ACID
* isolation
* indexes
* joins
* query execution basics

### OS

* process vs thread
* concurrency
* synchronization
* deadlock
* memory management
* virtual memory
* scheduling
* context switching

### CN

* OSI/TCP-IP concepts
* TCP vs UDP
* IP
* ports
* DNS
* HTTP/HTTPS
* TCP connection
* sockets
* routing basics
* common application-layer protocols

---

## 🟠 Strong Understanding

Know the concept clearly and explain it.

Do not spend excessive time memorizing textbook wording.

---

## 🟡 Learn / Use

Know what it is, where it is used, and understand the basic mechanism.

---

## 🟢 Skim

Understand enough to recognize the concept.

---

## ⚪ Skip for Now

Advanced academic details that provide poor ROI for the current target.

They may return later if:

* a company asks them
* a project requires them
* system design requires them
* internship/placement preparation indicates a gap

---

# 4. OOP Timing

OOP begins alongside Java.

This is intentional.

Java syntax without OOP understanding is insufficient.

The sequence should generally be:

Java classes
→ objects
→ constructors
→ encapsulation
→ inheritance
→ overriding
→ polymorphism
→ abstraction
→ interfaces
→ composition
→ SOLID/design principles

The roadmap should connect Java learning directly to OOP.

---

# 5. DBMS Timing

DBMS becomes significantly more important once SQL and backend development begin.

Sequence:

SQL basics
→ relational model
→ keys/constraints
→ normalization
→ joins
→ transactions
→ ACID
→ indexes
→ isolation
→ query optimization basics
→ database design

---

# 6. Operating Systems Timing

OS should not dominate early Java learning.

It becomes a dedicated interview subject after the technical foundation is established.

Core sequence:

OS fundamentals
→ processes
→ threads
→ scheduling
→ synchronization
→ deadlocks
→ memory
→ virtual memory
→ file systems / I/O basics

---

# 7. Computer Networks Timing

CN becomes especially meaningful once backend development starts.

Sequence:

networking basics
→ IP/ports
→ TCP/UDP
→ DNS
→ HTTP
→ HTTPS
→ client-server model
→ sockets
→ REST communication
→ APIs
→ practical backend networking

This allows theory to reinforce actual backend development.

---

# 8. Software Engineering

Focus on practical engineering:

* SDLC
* requirements
* version control
* testing
* debugging
* code review
* maintainability
* documentation
* Agile basics
* CI/CD concepts

Avoid excessive theoretical memorization.

---

# 9. System Design

System design is introduced only after sufficient backend foundation.

Prerequisites:

Java
→ SQL
→ Spring Boot
→ REST APIs
→ databases
→ authentication
→ caching basics
→ Docker
→ deployment
→ distributed-system fundamentals

Only then should serious system-design preparation begin.

---

# 10. Resource Strategy

The roadmap should select resources deliberately.

Preferred hierarchy:

### Primary

A clear structured course/resource appropriate to the topic.

### Secondary

Official documentation / authoritative references.

### Tertiary

Interview-focused resources for revision.

### Practice

Interview questions and project application.

Avoid collecting ten resources for the same subject.

---

# 11. Three-Level Core CS Notes

For important concepts:

### Tier 1 — Understanding Notes

Longer explanation.

### Tier 2 — Interview Notes

Condensed answer.

### Tier 3 — Rapid Revision

One-screen summary / flash points.

Example:

**TCP vs UDP**

Tier 1:
Detailed understanding.

Tier 2:
Interview-ready comparison.

Tier 3:
A few decisive differences.

---

# 12. Interview Answer Protocol

For a conceptual question:

### 1. Definition

What is it?

### 2. Purpose

Why does it exist?

### 3. Mechanism

How does it work?

### 4. Example

Where would you see it?

### 5. Trade-off

Why choose it over an alternative?

This produces stronger interview answers than memorizing definitions.

---

# 13. Connection Rule

Whenever possible, connect Core CS to:

* Java
* SQL
* Spring Boot
* REST APIs
* databases
* networking
* projects

Example:

**HTTP → REST API → Spring Boot Controller → TCP/IP → client-server communication**

The goal is integrated understanding.

---

# 14. Revision

Core CS should use:

* short post-learning revision
* weekly recall
* monthly consolidation
* interview-question revision
* pre-interview rapid revision

Do not repeatedly reread entire textbooks.

Use active recall.

---

# 15. Current Execution Requirement

The daily/weekly roadmap must specify:

* exact subject
* exact topic
* resource
* exact subsection/video where possible
* what to understand
* what to memorize
* practice questions
* revision task

Never:

> "Study OS."

Instead:

> "OS — Process vs Thread: understand address-space difference, context switching and scheduling implications; create a comparison note; answer 5 interview questions."

---

# 16. Final Goal

Core CS should become:

> **Interview-ready technical fluency, not academic perfection.**

The roadmap must balance:

**Depth × relevance × retention × time.**
