# Chapter 2: Manual Testing vs Automation Testing

## Learning Objectives

After completing this chapter, you will be able to:

* Understand manual testing.
* Understand automation testing.
* Explain how automation testing works.
* Understand why programming is required.
* Identify the advantages and limitations of both approaches.
* Know when to choose manual testing and when to choose automation testing.

---

# 1. What is Manual Testing?

Manual testing is the process of testing an application without using automation tools. A tester executes test cases manually and verifies whether the application behaves as expected.

## Example

Testing the login page manually:

1. Launch the application.
2. Enter a valid username.
3. Enter a valid password.
4. Click the **Login** button.
5. Verify that the dashboard is displayed.

If the expected result matches the actual result, the test case passes. Otherwise, a defect is reported.

---

# 2. Advantages of Manual Testing

* Easy to start without programming knowledge.
* Suitable for exploratory testing.
* Best for usability and user experience testing.
* Effective for testing newly developed features.
* Flexible when requirements change frequently.

---

# 3. Limitations of Manual Testing

* Time-consuming.
* Repetitive tasks can become tedious.
* Human errors may occur.
* Regression testing takes more time.
* Not suitable for executing thousands of test cases repeatedly.

---

# 4. What is Automation Testing?

Automation testing is the process of executing test cases using automation tools and scripts instead of performing them manually.

Popular automation tools include:

* Selenium
* Playwright
* Cypress
* Appium

Automation is especially useful for repetitive and regression test scenarios.

---

# 5. How Does Automation Testing Work?

The automation process follows these steps:

1. Create manual test cases.
2. Convert the manual steps into an automation script.
3. Write the script using a supported programming language (such as Java or Python).
4. Execute the script using an automation tool.
5. The tool performs the actions on the application.
6. The tool compares the actual result with the expected result.
7. A test execution report is generated.

## Workflow

Manual Test Case

↓

Automation Script

↓

Automation Tool

↓

Application Under Test (AUT)

↓

Execution

↓

Verification

↓

Test Report

---

# 6. Why is Programming Required?

Automation tools cannot understand plain English instructions. They understand programming languages.

For example, if Selenium is used with Java, the automation script is written in Java.

Example:

Manual instruction:

* Open the browser.
* Enter username.
* Enter password.
* Click Login.

Automation script:

```java
driver.get("https://example.com");

driver.findElement(By.id("username")).sendKeys("admin");

driver.findElement(By.id("password")).sendKeys("admin123");

driver.findElement(By.id("login")).click();
```

Programming makes automation possible by allowing the tester to communicate with the automation tool.

---

# 7. How Automation Helps in Re-Testing

Suppose a login defect has been fixed.

Instead of manually repeating the same test every time, an automation script can execute it whenever required.

Benefits:

* Faster execution.
* Consistent results.
* Less manual effort.
* Can be executed multiple times.

---

# 8. How Automation Helps in Regression Testing

Imagine the following situation:

**Test Cycle 1**

* Total Test Cases: 10
* Passed: 8
* Failed: 2

The 8 stable test cases are automated.

**Test Cycle 2**

* The 8 automated test cases run automatically.
* The 2 failed test cases are tested manually after fixes.

Once those are stable, they are also automated.

Over multiple releases:

* Manual effort decreases.
* Regression execution becomes faster.
* Test coverage increases.
* Release cycles become shorter.

This is one of the main reasons automation testing is widely used.

---

# 9. Manual Testing vs Automation Testing

| Manual Testing                             | Automation Testing                         |
| ------------------------------------------ | ------------------------------------------ |
| Performed by a tester                      | Performed using automation tools           |
| No programming required                    | Programming knowledge required             |
| Slower for repetitive tasks                | Faster for repetitive tasks                |
| Best for exploratory and usability testing | Best for regression and repetitive testing |
| Higher chance of human error               | Consistent execution                       |
| Lower initial setup cost                   | Higher initial setup cost                  |

---

# 10. Real-World Example

A company has 500 regression test cases.

If each test case takes 3 minutes:

* Manual execution: Approximately 25 hours.
* Automation execution: Around 2 hours (depending on infrastructure).

This saves significant time and allows faster software releases.

---

# Interview Questions

### 1. What is manual testing?

Manual testing is the process of verifying software functionality without using automation tools.

---

### 2. What is automation testing?

Automation testing is the process of executing test cases using automation tools and scripts.

---

### 3. Why is programming required for automation testing?

Programming is required because automation tools understand programming languages, not plain English instructions.

---

### 4. Why is automation mainly used for regression testing?

Automation allows repetitive test cases to be executed quickly, accurately, and repeatedly, making regression testing more efficient.

---

# Key Takeaways

* Manual testing is performed by humans.
* Automation testing uses tools and programming.
* Automation is ideal for repetitive and regression testing.
* Programming is an essential skill for automation testers.
* Automation improves speed, consistency, and test coverage.
