# Chapter 7: Severity vs Priority

## Learning Objectives

After completing this chapter, you will be able to:

* Understand what Severity is.
* Understand what Priority is.
* Differentiate between Severity and Priority.
* Learn different combinations of Severity and Priority.
* Answer common interview questions related to Severity and Priority.

---

# 1. What is Severity?

Severity indicates how serious a defect is and how much impact it has on the application's functionality.

Severity is generally decided by the QA Engineer.

---

# 2. Types of Severity

## Critical

A defect that causes the application to crash or prevents users from performing important business operations.

### Example

* Application crashes during payment.
* User cannot log in.

---

## High

A major functionality is not working, but the application is still usable.

### Example

* User cannot add items to the cart.
* Search functionality is not working.

---

## Medium

The defect affects functionality but has a workaround.

### Example

* Incorrect validation message.
* Profile picture is not updating.

---

## Low

Minor issues that do not affect functionality.

### Example

* UI alignment issue.
* Typographical errors.
* Incorrect icon.

---

# 3. What is Priority?

Priority indicates how quickly a defect should be fixed.

Priority is usually decided by the Product Owner, Project Manager, or Business Team.

---

# 4. Types of Priority

## High Priority

The defect must be fixed immediately.

### Example

* Payment failure.
* Login issue during production.

---

## Medium Priority

The defect should be fixed in the current release but is not urgent.

### Example

* Incorrect validation message.

---

## Low Priority

The defect can be fixed in a future release.

### Example

* Spelling mistakes.
* UI improvements.

---

# 5. Difference Between Severity and Priority

| Severity | Priority |
|----------|----------|
| Indicates the impact of a defect | Indicates the urgency to fix a defect |
| Decided by QA | Usually decided by Business/Product Team |
| Related to functionality | Related to business value |
| Measures technical impact | Measures business importance |

---

# 6. Severity vs Priority Combinations

## High Severity - High Priority

The defect has a major impact and must be fixed immediately.

### Example

* Payment gateway failure.
* User unable to log in.

---

## High Severity - Low Priority

The defect has a major impact but affects a rarely used feature.

### Example

* An issue in an Admin Report page used only once a year.

---

## Low Severity - High Priority

The defect has little technical impact but needs an immediate fix because it is visible to users.

### Example

* Company name spelled incorrectly on the Home Page.
* Wrong company logo displayed.

---

## Low Severity - Low Priority

Minor cosmetic issues that can be fixed later.

### Example

* Button alignment issue.
* Extra spaces in labels.
* Font size inconsistency.

---

# 7. Real-Time Example

Suppose you are testing an Online Shopping Application.

| Defect | Severity | Priority |
|---------|----------|----------|
| Payment not working | Critical | High |
| Login page crash | Critical | High |
| Typo in Privacy Policy | Low | Low |
| Wrong company logo on Home Page | Low | High |
| Admin report export issue | High | Low |

---

# 8. Best Practices

* Always understand the business impact before assigning severity.
* Clearly explain why a defect has a particular severity.
* Do not confuse Severity with Priority.
* Discuss critical defects with the Product Owner and Development Team.
* Follow your organization's defect classification guidelines.

---

# 9. Common Mistakes

* Treating Severity and Priority as the same.
* Assigning High Severity to every defect.
* Ignoring business impact.
* Not providing enough information in defect reports.

---

# Interview Questions

### 1. What is Severity?

Severity indicates how much impact a defect has on the application's functionality.

---

### 2. What is Priority?

Priority indicates how quickly a defect should be fixed.

---

### 3. Who decides Severity?

Generally, the QA Engineer decides the Severity of a defect.

---

### 4. Who decides Priority?

Priority is usually decided by the Product Owner, Business Team, or Project Manager.

---

### 5. Can a defect have High Severity and Low Priority?

Yes.

For example, a critical issue in a feature that is rarely used may have High Severity but Low Priority.

---

### 6. Can a defect have Low Severity and High Priority?

Yes.

For example, an incorrect company logo on the Home Page has low technical impact but high business impact.

---

# Key Takeaways

* Severity measures the impact of a defect.
* Priority measures the urgency to fix a defect.
* Severity is generally assigned by QA.
* Priority is generally assigned by the Business Team or Product Owner.
* Understanding both helps in effective defect management.
