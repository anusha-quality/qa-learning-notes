# Chapter 8: Smoke Testing vs Sanity Testing

## Learning Objectives

After completing this chapter, you will be able to:

* Understand what Smoke Testing is.
* Understand what Sanity Testing is.
* Differentiate between Smoke Testing and Sanity Testing.
* Know when to perform Smoke and Sanity Testing.
* Answer common interview questions.

---

# 1. What is Smoke Testing?

Smoke Testing is a type of software testing performed to verify whether the critical functionalities of an application are working after a new build is deployed.

Its purpose is to determine whether the build is stable enough for further testing.

Smoke Testing is also known as **Build Verification Testing (BVT).**

---

# 2. When is Smoke Testing Performed?

Smoke Testing is performed:

* After receiving a new build.
* Before detailed functional testing.
* Before regression testing begins.

---

# 3. Example of Smoke Testing

Suppose a new build of an E-Commerce application is deployed.

The QA Engineer checks:

* Application launches successfully.
* Login works.
* Home page loads.
* Product search works.
* Add to Cart works.
* Logout works.

If these critical functionalities work correctly, the build is accepted for further testing.

---

# 4. Advantages of Smoke Testing

* Detects major issues early.
* Saves testing effort.
* Ensures build stability.
* Prevents wasting time on unstable builds.

---

# 5. Limitations of Smoke Testing

* Covers only critical functionality.
* Does not perform detailed validation.
* Cannot detect all defects.

---

# 6. What is Sanity Testing?

Sanity Testing is a type of testing performed after receiving a bug fix or a minor change to verify that the specific functionality works correctly.

It ensures that the defect has been fixed without affecting related functionality.

---

# 7. When is Sanity Testing Performed?

Sanity Testing is performed:

* After a bug fix.
* After minor code changes.
* Before regression testing.

---

# 8. Example of Sanity Testing

Suppose the Login button was not working.

The developer fixes the issue and provides a new build.

The QA Engineer verifies:

* Login functionality.
* Related validations.
* Navigation after login.

If the fix works correctly, testing continues.

---

# 9. Advantages of Sanity Testing

* Verifies bug fixes quickly.
* Saves testing time.
* Focuses only on changed functionality.
* Ensures recent fixes work correctly.

---

# 10. Limitations of Sanity Testing

* Limited test coverage.
* Does not verify the complete application.
* May miss defects in unaffected modules.

---

# 11. Difference Between Smoke Testing and Sanity Testing

| Smoke Testing | Sanity Testing |
|---------------|----------------|
| Performed on a new build | Performed after bug fixes |
| Verifies build stability | Verifies specific functionality |
| Covers major functionalities | Covers modified functionality |
| Wide and shallow testing | Narrow and deep testing |
| Performed before detailed testing | Performed after receiving a fixed build |

---

# 12. Real-Time Example

Suppose your company releases Version 2.0 of a Banking Application.

### Smoke Testing

QA verifies:

* Login
* Dashboard
* Account Summary
* Fund Transfer
* Logout

Everything works.

Testing proceeds.

---

A bug is found in Fund Transfer.

The developer fixes the issue.

### Sanity Testing

QA verifies:

* Fund Transfer
* Balance Update
* Transaction History

Everything works.

Testing continues.

---

# 13. Best Practices

* Always perform Smoke Testing on every new build.
* Perform Sanity Testing after bug fixes.
* Do not skip Smoke Testing before detailed testing.
* Document Smoke and Sanity test results.
* Automate Smoke Tests whenever possible.

---

# 14. Common Mistakes

* Confusing Smoke Testing with Sanity Testing.
* Performing detailed testing during Smoke Testing.
* Skipping Smoke Testing.
* Assuming Sanity Testing replaces Regression Testing.

---

# Interview Questions

### 1. What is Smoke Testing?

Smoke Testing verifies whether the critical functionalities of an application work correctly after receiving a new build.

---

### 2. What is Sanity Testing?

Sanity Testing verifies whether a specific bug fix or change works correctly.

---

### 3. What is another name for Smoke Testing?

Build Verification Testing (BVT).

---

### 4. Which testing is performed after a new build?

Smoke Testing.

---

### 5. Which testing is performed after a bug fix?

Sanity Testing.

---

### 6. Does Sanity Testing replace Regression Testing?

No.

Sanity Testing verifies only the changed functionality, whereas Regression Testing verifies that existing functionalities continue to work correctly.

---

# Key Takeaways

* Smoke Testing checks build stability.
* Sanity Testing checks bug fixes.
* Smoke Testing is wide and shallow.
* Sanity Testing is narrow and deep.
* Both help improve software quality and reduce testing effort.
