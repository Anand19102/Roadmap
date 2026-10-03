# 🚫 NO TUTORIAL-COPYING RULE
## Project Learning & Independent Engineering Protocol

> **Purpose:** Prevent tutorial hell, passive learning, fake project experience, and the illusion of understanding.

---

## 1. THE CORE RULE

> **A project only counts as learning if I make meaningful engineering decisions myself.**

Watching someone build a project and reproducing their code line-by-line is **not** considered genuine project completion.

A tutorial can teach me:
- concepts
- architecture
- technologies
- implementation patterns
- debugging approaches
- engineering practices

But the tutorial must not become a substitute for my own thinking.

---

## 2. WHAT COUNTS AS TUTORIAL COPYING?

The following are considered copying:
- typing code simultaneously with the instructor
- copying the entire repository
- copying code without understanding why it works
- copying the same UI/API/database structure
- copying the same feature list
- copying the same architecture
- watching the tutorial and then claiming I "built" the project
- changing variable names and considering the project original
- asking AI to reproduce the tutorial project
- following a tutorial so closely that I make almost no design decisions myself

---

## 3. WHAT IS ALLOWED?

Tutorials are allowed. The problem is **dependency**, not tutorials themselves.

A tutorial may be used to:
- understand Spring Boot
- understand REST APIs
- learn JPA
- learn authentication
- understand Docker
- understand deployment
- understand project architecture
- learn unfamiliar libraries
- see how experienced developers approach problems

The objective is:
> **Learn from the tutorial → close it → build independently.**

---

## 4. THE PROJECT LEARNING CYCLE

Every serious tutorial-based learning project should follow:

```text
LEARN
  ↓
UNDERSTAND
  ↓
CLOSE THE TUTORIAL
  ↓
RECALL
  ↓
DESIGN MY OWN VERSION
  ↓
IMPLEMENT
  ↓
DEBUG
  ↓
DOCUMENT
  ↓
EXTEND
  ↓
EXPLAIN
```

---

## 5. THE "CLOSE THE TUTORIAL" RULE

After learning a feature from a tutorial:
1. Stop the video.
2. Close the source code.
3. Do not copy the implementation.
4. Recreate the feature from memory.
5. If stuck, identify the specific concept causing the problem.
6. Refer back only to that concept.
7. Close the source again.
8. Continue independently.

This converts passive watching into active learning.

---

## 6. THE THREE-LEVEL PROJECT RULE

### Level 1 — Guided Micro-Project
* **Tutorial usage:** 🟢 High
* **Purpose:** learn syntax, understand tools, understand basic workflow, become comfortable with IDE/Git/framework.
> Copying small pieces is acceptable when explicitly being used as learning material. However, I must understand every important line I retain.

### Level 2 — Tutorial-Inspired Project
* **Tutorial usage:** 🟡 Moderate
* I may learn the general architecture from a tutorial, but I must change: domain, requirements, database schema, endpoints, features, naming, business logic, UI where applicable, edge cases.
> The final project should require independent decisions.

### Level 3 — Serious Portfolio Project
* **Tutorial usage:** 🔴 Minimal
* A serious portfolio project should NOT be: *"I followed a YouTube tutorial and built this."*
* Instead:
```text
Problem → Requirements → Architecture → Technology selection → Database design → API design → Implementation → Testing → Security → Deployment → Documentation → Iteration
```
Tutorials may be consulted for individual unfamiliar concepts, but the project itself must be independently designed.

---

## 7. BEFORE STARTING A PROJECT

Write down:
* **Problem:** What problem am I solving?
* **Users:** Who would use this?
* **Requirements:** What must the system do?
* **Constraints:** What limitations exist?
* **Features:** What are the core features?
* **Data:** What information needs to be stored?
* **Architecture:** What components are required?
* **Technology:** Why am I choosing each technology?

---

## 8. BUILD WITHOUT LOOKING FIRST

Before opening a tutorial, try to build the feature myself.
Example: *"I need a POST endpoint that creates a user."*

First attempt:
1. create controller
2. define request DTO
3. validate input
4. call service
5. save entity
6. return response

Only after attempting it should I consult external material.

---

## 9. THE 20-MINUTE RULE

When stuck:
* **First 5 minutes:** Think independently.
* **Next 5 minutes:** Read compiler error, stack trace, documentation, IDE hints.
* **Next 10 minutes:** Search specifically for the problem.
> Do not immediately search: *"complete Spring Boot project code"*
> Instead search: *"Spring Boot validation error X"* or *"JPA lazy loading exception cause"*

The narrower the question, the better the learning.

---

## 10. THE EXPLANATION TEST

A project feature is not considered learned until I can explain:
- What it does
- Why it exists
- How it works
- Why I implemented it this way
- What alternatives exist
- What could go wrong
- How I would modify it

If I cannot explain it, I do not truly own the knowledge.

---

## 11. THE MODIFICATION TEST

After completing a tutorial-inspired project, I must modify it without following the tutorial. Examples:
- add a new feature
- change the database model
- add pagination/sorting
- change authentication
- introduce validation
- add caching
- add a new API
- change the frontend
- containerize it
- deploy it

If I can extend the project independently, the tutorial has served its purpose.

---

## 12. THE REBUILD TEST

For important technologies, build the core functionality again from a blank project.

**Spring Boot:**
Independently create project, controller, service, repository, entity, DTO, database connection, REST endpoint.

**SQL:**
Given a schema, independently write SELECT, JOIN, GROUP BY, subquery, CTE, window function.

**DSA:**
Given a problem, independently recognize pattern, derive approach, write algorithm, code it, analyze complexity.

---

## 13. TUTORIAL NOTES

Do not create notes that simply reproduce the instructor's notes. Instead record:
* **Concept:** What did I learn?
* **Why:** Why does it matter?
* **Pattern:** When do I use it?
* **Mistake:** What confused me?
* **Application:** Where can I use it?
* **Personal understanding:** How would I explain it?

---

## 14. PROJECT AUTHENTICITY CHECK

Before calling a project complete:
- [ ] I understand the architecture.
- [ ] I understand the database design.
- [ ] I understand the important code.
- [ ] I can explain the project.
- [ ] I can modify the project.
- [ ] I can debug the project.
- [ ] I can add a feature without the tutorial.
- [ ] I know why I chose the major technologies.
- [ ] I know the project's limitations.
- [ ] I can discuss it in an interview.

If several answers are "no": The project is still a learning project, not a finished portfolio project.

---

## 15. THE GOLDEN RULE

Tutorials teach me how something can be built. Independent implementation teaches me that I can build it.

The roadmap must progressively move from:
```text
FOLLOW → UNDERSTAND → MODIFY → BUILD → DESIGN → ENGINEER
```
The ultimate goal is engineering independence.