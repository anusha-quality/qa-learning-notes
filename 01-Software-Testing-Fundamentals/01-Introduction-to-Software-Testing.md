# Chapter 1: Introduction to Software Testing

## Learning Objectives

After completing this chapter, you will be able to:

* Understand what software testing is.
* Explain the purpose of software testing.
* Identify different types of applications.
* Differentiate between manual and automation testing.
* Explain re-testing and regression testing.
* Understand why programming is required for automation testing.
* Describe how automation testing works.

---

# 1. What is Software Testing?

Software testing is the process of verifying and validating a software application to ensure it meets business requirements and is free from defects before it is released to customers.

The main objective of software testing is to deliver a high-quality, reliable, and user-friendly application.

### Example

Suppose an online shopping application allows customers to purchase products.

Before releasing it, a tester verifies:

* Login functionality
* Product search
* Add to Cart
* Payment process
* Order confirmation

If any issue is found, it is reported to the development team for fixing.

---

# 2. Why is Software Testing Important?

Software testing helps to:

* Detect defects before release.
* Improve software quality.
* Reduce production issues.
* Increase customer satisfaction.
* Ensure business requirements are met.

---

# 3. Types of Applications

Applications are generally classified into three categories.

## Web Applications

Applications that run in a web browser.

Examples:

* Amazon
* Gmail
* Facebook
* Flipkart

---

## Desktop Applications

Applications installed directly on a computer.

Examples:

* Calculator
* Notepad
* Microsoft Word
* Paint

---

## Mobile Applications

Applications developed for Android or iOS devices.

Examples:

* WhatsApp
* Instagram
* PhonePe
* Google Pay

---

# 4. What is Manual Testing?

Manual testing is the process of testing software without using automation tools.

The tester manually executes test cases, verifies results, and reports defects.

### Example

To test the login feature:

1. Launch the application.
2. Enter a valid username.
3. Enter a valid password.
4. Click **Login**.
5. Verify that the dashboard is displayed.

---

# 5. What is a Test Case?

A test case is a document containing step-by-step instructions to verify a specific functionality of an application.

A typical test case includes:

* Test Case ID
* Test Scenario
* Preconditions
* Test Steps
* Test Data
* Expected Result
* Actual Result
* Status

---

# 6. What is Re-Testing?

Re-testing is performed to verify that a defect reported earlier has been fixed successfully.

### When is Re-Testing performed?

* After the developer fixes a bug.
* Only the failed test case is executed again.

### Example

A login defect prevented users from signing in with valid credentials.

After the fix, the same login test case is executed again to confirm that the issue has been resolved.

---

# 7. What is Regression Testing?

Regression testing verifies that recent changes or bug fixes have not affected existing functionality.

### When is Regression Testing performed?

* After bug fixes.
* After new feature implementation.
* Before a release.
* After code changes.

### Example

If the login module is updated, regression testing may also include:

* Registration
* Search
* Cart
* Checkout
* User Profile

This ensures that existing features continue to work correctly.

---

# 8. Difference Between Re-Testing and Regression Testing

| Re-Testing                   | Regression Testing                            |
| ---------------------------- | --------------------------------------------- |
| Verifies a fixed defect      | Verifies existing functionality after changes |
| Focuses on failed test cases | Covers impacted and existing areas            |
| Usually manual               | Often automated                               |
| Ensures the bug is fixed     | Ensures nothing else is broken                |

---

# Summary

In this chapter, you learned:

* The purpose of software testing.
* Different types of applications.
* Manual testing basics.
* Test cases.
* Re-testing.
* Regression testing.

These concepts form the foundation for understanding automation testing and Selenium in the next chapters.
