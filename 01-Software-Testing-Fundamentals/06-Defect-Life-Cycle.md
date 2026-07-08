# Chapter 6: Defect Life Cycle (Bug Life Cycle)

## Learning Objectives

After completing this chapter, you will be able to:

* Understand what a defect is.
* Learn the stages of the Defect Life Cycle.
* Understand the responsibilities of QA Engineers and Developers.
* Learn common defect statuses used in projects.
* Answer common interview questions related to Defect Life Cycle.

---

# 1. What is a Defect?

A defect (also called a bug) is a flaw or issue in a software application where the actual result does not match the expected result.

A defect is identified during testing and reported to the development team for resolution.

---

# 2. What is the Defect Life Cycle?

The Defect Life Cycle is the process that a defect follows from the time it is identified until it is fixed and closed.

It helps teams track the progress of defects and ensures that every reported issue is resolved properly.

---

# 3. Defect Life Cycle Stages

1. New
2. Assigned
3. Open
4. Fixed
5. Retest
6. Closed
7. Reopened
8. Deferred
9. Rejected
10. Duplicate

---

# 4. New

A tester identifies a defect and logs it in the defect tracking tool (such as Jira).

### Example

While testing the Login page, clicking the Login button does not redirect the user to the Dashboard.

Status: **New**

---

# 5. Assigned

The Test Lead or Project Manager assigns the defect to the appropriate developer.

Status: **Assigned**

---

# 6. Open

The developer reviews the defect, analyzes the root cause, and starts working on fixing it.

Status: **Open**

---

# 7. Fixed

The developer resolves the issue and marks the defect as **Fixed**.

The defect is then assigned back to the QA team for verification.

---

# 8. Retest

The QA Engineer verifies whether the reported defect has been fixed.

If the issue no longer exists, the defect moves to **Closed**.

---

# 9. Closed

If the defect is fixed successfully and works as expected, the QA Engineer closes the defect.

Status: **Closed**

---

# 10. Reopened

If the issue still exists after the developer marks it as Fixed, the QA Engineer changes the status to **Reopened**.

The defect is reassigned to the developer for another fix.

---

# 11. Deferred

Sometimes a defect is not fixed in the current release because:

* Low priority
* Business decision
* Time constraints

The defect is postponed to a future release.

Status: **Deferred**

---

# 12. Rejected

The developer or Product Owner may reject a defect if:

* The issue is not reproducible.
* The application is working as designed.
* It is not considered a defect.

Status: **Rejected**

---

# 13. Duplicate

If the same defect has already been reported by another tester, the new defect is marked as **Duplicate**.

This avoids maintaining multiple tickets for the same issue.

---

# 14. Defect Life Cycle Workflow

```text
New
 ↓
Assigned
 ↓
Open
 ↓
Fixed
 ↓
Retest
 ↓
Closed

If not fixed

Retest
 ↓
Reopened
 ↓
Assigned
 ↓
Open
 ↓
Fixed
 ↓
Retest
 ↓
Closed
```

---

# 15. Real-World Example

Suppose you are testing an Online Banking application.

### Issue

The user enters valid credentials but cannot log in.

### Defect Flow

* QA logs the defect as **New**.
* Test Lead assigns it to a Developer.
* Developer changes the status to **Open**.
* Developer fixes the issue and marks it as **Fixed**.
* QA performs Re-testing.
* Login works correctly.
* QA marks the defect as **Closed**.

---

# 16. Best Practices for Defect Reporting

* Use a clear and meaningful defect summary.
* Provide detailed reproduction steps.
* Mention expected and actual results.
* Attach screenshots or screen recordings when possible.
* Mention environment details.
* Assign the correct Severity and Priority.
* Retest before closing the defect.

---

# 17. Common Defect Tracking Tools

* Jira
* Azure DevOps
* Bugzilla
* Redmine
* MantisBT

---

# Interview Questions

### 1. What is a defect?

A defect is a mismatch between the expected result and the actual result in a software application.

---

### 2. What is the Defect Life Cycle?

The Defect Life Cycle is the journey of a defect from identification until closure.

---

### 3. What happens after a defect is Fixed?

The QA Engineer performs Re-testing to verify whether the issue has been resolved.

---

### 4. What is the difference between Reopened and Rejected?

**Reopened:** The defect still exists after the fix.

**Rejected:** The issue is not considered a valid defect.

---

### 5. Why is the Duplicate status used?

Duplicate status is used when the same defect has already been reported, preventing multiple defect tickets for the same issue.

---

# Key Takeaways

* Every reported defect follows a defined life cycle.
* QA and Developers work together to resolve defects.
* Proper defect tracking improves software quality.
* Clear defect reports help developers fix issues faster.
* Understanding the Defect Life Cycle is essential for every QA Engineer.
