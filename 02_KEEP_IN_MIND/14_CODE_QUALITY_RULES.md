# 🧼 CODE QUALITY RULES
## Engineering Standards for Java, DSA, Backend & Projects

---

## 1. PURPOSE

The goal is to progress from: *"Code that works"*
to: **"Code that is correct, readable, maintainable and explainable."**

---

## 2. CORRECTNESS FIRST

Priority:
```text
Correctness → Clarity → Maintainability → Performance → Optimization
```
Do not prematurely optimize.

---

## 3. NAMING & METHODS

* **Names:** Should communicate purpose. Prefer `studentCount`, `maximumValue`, `userRepository` over `x`, `a`, `temp1`, `abc` unless the variable is genuinely temporary and obvious.
* **Methods:** A method should ideally have one clear responsibility, understandable inputs, understandable output, and manageable length. Avoid giant methods containing everything.

---

## 4. COMMENTS & DUPLICATION

* **Comments:** Should explain WHY not merely WHAT.
  * *Bad:* `// increment i`
  * *Useful:* `// Move the left pointer because the current sum is too large.`
* **Duplication:** Avoid unnecessary repeated logic. Consider extracting it. However: Do not create abstractions merely to avoid two repeated lines.

---

## 5. ERROR HANDLING

Do not silently ignore errors.
Backend applications should eventually handle: invalid input, missing resources, unauthorized access, database failures, unexpected exceptions.

---

## 6. DSA VS PROJECT CODE

* **DSA Code:** Should prioritize clarity, standard patterns, correct complexity, reusable templates. Do not over-engineer LeetCode solutions.
* **Project Code:** Should progressively demonstrate separation of concerns, modularity, appropriate abstraction, validation, error handling, testing, meaningful naming.

---

## 7. FORMATTING & SECURITY

* **Formatting:** Use consistent indentation, braces, spacing, naming, file organization. Use IDE formatting tools.
* **Security:** Never hard-code passwords, API keys, tokens, secrets. Use appropriate configuration/environment mechanisms.

---

## 8. CODE REVIEW QUESTIONS

Before considering code finished:
- Is it correct?
- Is it understandable?
- Is it unnecessarily complex?
- Are edge cases handled?
- Are names meaningful?
- Is duplication justified?
- Can another developer understand it?
- Can I explain it?

---

## 9. GOLDEN RULE

Write code for the next developer who has to understand it — even if that developer is future me.