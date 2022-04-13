List of checkpoint to verify/do before merging a PR.

**Dev checklist:**

* [ ] Write/update UTs
* [ ] Write/update ITs
* [ ] Functional validation
* [ ] Public documentation update
* [ ] Private documentation update
* [ ] Clean commits (should start with a ticket number, clear message, no fixup, wip)
* [ ] Address all code quality issues, including code smells, even if QG is green
* [ ] Maximize code coverage as much as possible
* [ ] Database migrations are covered with Blue/Green deployment tests

**Reviewer checklist:**

* [ ] Code review
* [ ] Functional validation
* [ ] Check commits are clean
* [ ] Check that all code quality issues are fixed and coverage is maximized (even if the QG is green)
* [ ] Check that database migrations are Blue/Green compatible (especially in the case of a column/table deletion)
