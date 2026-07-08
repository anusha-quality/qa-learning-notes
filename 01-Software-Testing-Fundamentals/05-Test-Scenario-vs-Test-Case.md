# Chapter 5: Test Scenario vs Test Case

## Learning Objectives

After completing this chapter, you will be able to:

* Understand what a Test Scenario is.
* Understand what a Test Case is.
* Differentiate between a Test Scenario and a Test Case.
* Learn how to write effective Test Scenarios and Test Cases.
* Understand the importance of both in software testing.
* Answer common interview questions related to Test Scenarios and Test Cases.

---

# 1. What is a Test Scenario?

A Test Scenario is a high-level statement that describes what needs to be tested in an application.

It identifies the functionality or feature to be tested without going into detailed steps.

### Example

Module: Login

Test Scenario:

* Verify login functionality with valid credentials.
* Verify login with invalid credentials.
* Verify forgot password functionality.
* Verify remember me functionality.

---

# 2. Characteristics of a Test Scenario

* High-level description.
* Covers a single functionality.
* Helps identify test coverage.
* Created before writing Test Cases.
* Easy to understand.

---

# 3. What is a Test Case?

A Test Case is a detailed document that contains step-by-step instructions to verify a specific functionality of an application.

It includes test data, execution steps, expected results, and actual results.

---

# 4. Components of a Test Case

A standard Test Case contains the following fields:

* Test Case ID
* Test Scenario ID
* Test Scenario
* Test Case Description
* Preconditions
* Test Data
* Test Steps
* Expected Result
* Actual Result
* Status (Pass/Fail)
* Defect ID (if failed)
* Executed By
* Executed Date

---

# 5. Sample Test Case

| Date | Test Scenario ID | Test Scenario | Test Case ID | Test Case | Steps | Expected Result | Actual Result | Status | Executed Date |
|------|------------------|---------------|--------------|-----------|-------|-----------------|---------------|--------|---------------|
| 08-Jul-2026 | TS_LOGIN_001 | Verify Login | TC_LOGIN_001 | Verify login with valid credentials | 1. Launch application<br>2. Enter valid username<br>3. Enter valid password<br>4. Click Login | User should be redirected to the Dashboard | User successfully logged in | Pass | 08-Jul-2026 |

---

# 6. Difference Between Test Scenario and Test Case

| Test Scenario | Test Case |
|--------------|-----------|
| High-level description | Detailed step-by-step document |
| Describes *what* to test | Describes *how* to test |
| Covers a feature or functionality | Covers a specific validation |
| Fewer in number | More in number |
| Created before Test Cases | Created after Test Scenarios |

---

# 7. Example

## Feature

Login

### Test Scenario

Verify Login Functionality

### Test Cases

* Verify login with valid username and valid password.
* Verify login with invalid username.
* Verify login with invalid password.
* Verify login with blank username.
* Verify login with blank password.
* Verify login with both fields blank.
* Verify login using the Enter key.
* Verify Remember Me functionality.
* Verify Forgot Password functionality.
* Verify account lock after multiple failed attempts.

---

# 8. Best Practices for Writing Test Scenarios

* Understand the business requirements.
* Cover all major functionalities.
* Keep scenarios simple and clear.
* Avoid duplicate scenarios.
* Ensure complete functional coverage.

---

# 9. Best Practices for Writing Test Cases

* Write clear and detailed steps.
* Use unique Test Case IDs.
* Include expected results.
* Include positive and negative test cases.
* Cover boundary and validation scenarios.
* Review Test Cases before execution.

---

# 10. Real-World Example

Suppose you are testing an E-Commerce application.

### Test Scenario

Verify Add to Cart functionality.

### Test Cases

* Add one product to the cart.
* Add multiple products.
* Remove a product from the cart.
* Update product quantity.
* Verify total price calculation.
* Verify cart after user logout.
* Verify cart after browser refresh.

---

# 11. Advantages of Test Scenarios

* Easy to prepare.
* Helps estimate testing effort.
* Ensures functional coverage.
* Improves requirement understanding.

---

# 12. Advantages of Test Cases

* Provides detailed testing instructions.
* Ensures consistent execution.
* Improves defect detection.
* Helps during regression testing.
* Useful for future releases.

---

# 13. Limitations

### Test Scenario

* Does not contain execution steps.
* Cannot be directly executed.

### Test Case

* Time-consuming to prepare.
* Requires regular maintenance.
* Needs updates when requirements change.

---

# Interview Questions

### 1. What is a Test Scenario?

A Test Scenario is a high-level description of a functionality that needs to be tested.

---

### 2. What is a Test Case?

A Test Case is a detailed document containing test steps, test data, expected results, and actual results used to verify a specific functionality.

---

### 3. Which comes first: Test Scenario or Test Case?

Test Scenario is created first, followed by detailed Test Cases.

---

### 4. Can one Test Scenario have multiple Test Cases?

Yes. A single Test Scenario can have multiple Test Cases to validate different conditions.

---

### 5. Why are Test Cases important?

Test Cases ensure systematic testing, improve coverage, support regression testing, and provide documentation for future testing cycles.

---

# Key Takeaways

* Test Scenario defines **what** needs to be tested.
* Test Case defines **how** to test it.
* One Test Scenario can have multiple Test Cases.
* Well-written Test Cases improve software quality.
* Test Scenarios and Test Cases are essential artifacts in Manual Testing.
