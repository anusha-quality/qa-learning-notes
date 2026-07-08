# Chapter 4: Software Testing Life Cycle (STLC)

## Learning Objectives

After completing this chapter, you will be able to:

* Understand what STLC is.
* Learn the different phases of the Software Testing Life Cycle.
* Understand the deliverables of each phase.
* Learn the role of a QA Engineer during STLC.
* Answer common STLC interview questions.

---

# 1. What is STLC?

Software Testing Life Cycle (STLC) is a systematic process followed by the QA team to ensure that software is tested efficiently and meets the specified quality standards.

Each phase in STLC has specific objectives, activities, and deliverables.

---

# 2. Why Do We Need STLC?

STLC helps to:

* Improve software quality.
* Detect defects early.
* Ensure complete test coverage.
* Reduce testing effort.
* Deliver a quality product to customers.

---

# 3. Phases of STLC

The Software Testing Life Cycle consists of the following phases:

1. Requirement Analysis
2. Test Planning
3. Test Case Development
4. Test Environment Setup
5. Test Execution
6. Defect Reporting and Tracking
7. Test Cycle Closure

---

# 4. Requirement Analysis

In this phase, the QA team studies and understands the business requirements.

### Activities

* Review requirement documents.
* Identify testable requirements.
* Clarify doubts with the Business Analyst or Product Owner.
* Identify automation feasibility.

### Participants

* QA Engineer
* Business Analyst
* Product Owner

### Deliverables

* Requirement Analysis Document
* Requirement Clarifications

---

# 5. Test Planning

The Test Lead prepares the testing strategy for the project.

### Activities

* Define testing scope.
* Identify testing types.
* Estimate effort.
* Allocate resources.
* Prepare the test schedule.

### Participants

* Test Lead
* QA Manager
* Project Manager

### Deliverables

* Test Plan
* Resource Plan
* Test Schedule

---

# 6. Test Case Development

The QA team prepares all required test artifacts.

### Activities

* Write test scenarios.
* Create test cases.
* Prepare test data.
* Review test cases.
* Create the Requirement Traceability Matrix (RTM).

### Deliverables

* Test Cases
* Test Data
* RTM

---

# 7. Test Environment Setup

The testing environment is prepared before execution.

### Activities

* Configure servers.
* Deploy the application.
* Verify database connectivity.
* Validate test environment readiness.

### Participants

* DevOps Team
* Developers
* QA Engineers

### Deliverables

* Test Environment
* Environment Readiness Report

---

# 8. Test Execution

The QA team executes all planned test cases.

### Activities

* Execute test cases.
* Compare actual and expected results.
* Mark test cases as Pass or Fail.
* Report defects.

### Deliverables

* Test Execution Report
* Defect Report

---

# 9. Defect Reporting and Tracking

All identified defects are logged and tracked until closure.

### Activities

* Report defects in Jira or other defect tracking tools.
* Assign defects to developers.
* Perform Re-testing.
* Perform Regression Testing.
* Verify defect closure.

### Deliverables

* Defect Report
* Defect Status Report

---

# 10. Test Cycle Closure

After testing is completed, the QA team evaluates the testing process.

### Activities

* Analyze test results.
* Prepare Test Summary Report.
* Discuss lessons learned.
* Archive test artifacts.

### Deliverables

* Test Summary Report
* Test Metrics
* Lessons Learned Document

---

# 11. STLC Workflow

```text
Requirement Analysis
        ↓
Test Planning
        ↓
Test Case Development
        ↓
Test Environment Setup
        ↓
Test Execution
        ↓
Defect Reporting & Tracking
        ↓
Test Cycle Closure
```

---

# 12. Role of a QA Engineer in STLC

A QA Engineer is responsible for:

* Understanding requirements.
* Preparing test scenarios and test cases.
* Executing test cases.
* Reporting and tracking defects.
* Performing Re-testing.
* Performing Regression Testing.
* Preparing test reports.

---

# 13. Real-World Example

Suppose an e-commerce company launches a new payment feature.

### Requirement Analysis

QA studies payment requirements.

### Test Planning

The QA team estimates effort and prepares the test plan.

### Test Case Development

Test cases are created for:

* Credit Card
* Debit Card
* UPI
* Net Banking
* Wallet Payments

### Environment Setup

The UAT environment is configured.

### Test Execution

QA executes all payment scenarios.

### Defect Reporting

Payment failures are reported in Jira.

### Test Closure

A Test Summary Report is shared with stakeholders.

---

# 14. Advantages of STLC

* Improves software quality.
* Ensures structured testing.
* Better defect management.
* Better test coverage.
* Reduces production issues.
* Improves customer satisfaction.

---

# 15. Limitations of STLC

* Requires proper planning.
* Documentation takes time.
* Frequent requirement changes may affect testing.
* Depends on requirement quality.

---

# Interview Questions

### 1. What is STLC?

Software Testing Life Cycle (STLC) is a structured testing process followed by the QA team to verify and validate software quality.

---

### 2. What are the phases of STLC?

* Requirement Analysis
* Test Planning
* Test Case Development
* Test Environment Setup
* Test Execution
* Defect Reporting and Tracking
* Test Cycle Closure

---

### 3. What is the difference between SDLC and STLC?

| SDLC | STLC |
|------|------|
| Focuses on software development | Focuses on software testing |
| Followed by the development team | Followed by the QA team |
| Includes development activities | Includes testing activities |

---

### 4. What is the output of the Test Planning phase?

The main output is the **Test Plan** document.

---

### 5. Which STLC phase comes after Test Case Development?

**Test Environment Setup.**

---

# Key Takeaways

* STLC is a structured testing process.
* It consists of seven phases.
* Each phase has defined activities and deliverables.
* QA Engineers play an important role throughout STLC.
* Following STLC improves software quality and testing efficiency.
