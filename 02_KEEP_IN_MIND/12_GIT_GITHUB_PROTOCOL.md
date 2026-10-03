# 🌿 GIT & GITHUB PROTOCOL
## Version Control, Repository & Collaboration System

---

## 1. PURPOSE

Git is not merely something to add to a resume. It is the standard mechanism for:
- version control
- experimentation
- rollback
- collaboration
- code review
- project history

GitHub becomes the public portfolio layer.

---

## 2. FUNDAMENTAL CONCEPTS

Understand deeply: repository, working tree, staging area, commit, branch, merge, remote, clone, pull, push, pull request, conflict.
Do not memorize commands without understanding their purpose.

---

## 3. CORE COMMANDS

Master practical usage of:
```bash
git init
git clone
git status
git add
git commit
git log
git diff
git branch
git switch
git merge
git pull
git push
git remote
```

---

## 4. COMMIT PHILOSOPHY

A commit should represent a meaningful change.
* ✅ Good: `Add user registration endpoint`
* ❌ Bad: `update`
* ❌ Bad: `final final 2`

---

## 5. COMMIT FREQUENCY

Do not commit every keystroke. Commit after a meaningful unit of work.
Examples: add authentication, implement user repository, add validation, fix login bug, add pagination.

---

## 6. BRANCHING

Understand:
```text
main
│
├── feature/authentication
├── feature/pagination
└── feature/search
```
For larger projects, use feature branches. For small learning projects, simple main-branch development may be sufficient.

---

## 7. GITHUB REPOSITORY STANDARD

Serious repositories should contain: `README.md`, `.gitignore`, source code, tests, configuration documentation.
**Never commit:** passwords, API keys, tokens, private credentials, `.env` secrets, unnecessary build artifacts.

---

## 8. README STANDARD

A serious project README should answer:
- What is this?
- What problem does it solve?
- What technologies are used?
- How is it structured?
- How do I run it?
- What are the major APIs/features?
- What are the important engineering decisions?
- What are future improvements?

---

## 9. GIT HISTORY

Avoid fake histories. Do not:
- create hundreds of meaningless commits
- deliberately manipulate commit dates
- commit entire projects in one giant meaningless dump

Use Git naturally during development.

---

## 10. BRANCH CONFLICTS

Learn how to: identify conflict, inspect conflicting files, decide correct version, edit conflict markers, stage resolution, commit/continue merge.
Do not blindly choose "ours" or "theirs" without understanding the change.

---

## 11. GITHUB AS PORTFOLIO

Eventually:
* **Pin:** Only the strongest repositories.
* **Clean:** Remove abandoned junk from public view where appropriate.
* **Document:** Make important projects easy to understand.
* **Demonstrate:** Use README files effectively.

---

## 12. GIT LEARNING DEPTH

* 🔴 **MASTER:** status, add, commit, log, diff, branch, switch, merge, pull, push, remote, conflict resolution, .gitignore
* 🟠 **STRONG UNDERSTANDING:** rebasing, cherry-pick, stash, reset, revert, tags
* 🟡 **LEARN/USE:** Advanced collaboration workflows when encountered.
* 🟢 **SKIM:** Rarely used internals.
* ⚪ **SKIP FOR NOW:** Deep Git implementation internals.

---

## 13. GOLDEN RULE

Git should document my development process, not become another subject I endlessly study.