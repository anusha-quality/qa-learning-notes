# Chapter 10: Testing Levels

## Learning Objectives

After completing this chapter, you will be able to:

* Understand the different levels of software testing.
* Learn the purpose of each testing level.
* Identify who performs each level of testing.
* Differentiate between Unit, Integration, System, and User Acceptance Testing (UAT).
* Answer common interview questions.

---

# 1. What are Testing Levels?

Testing Levels define the different stages at which software is tested during the Software Development Life Cycle (SDLC).

Each level has a specific objective and helps identify defects at different stages of development.

The four main testing levels are:

1. Unit Testing
2. Integration Testing
3. System Testing
4. User Acceptance Testing (UAT)

---

# 2. Unit Testing

Unit Testing is the first level of testing.

It verifies the smallest unit or component of an application independently.

### Performed By

* Developers

### Objective

* Verify individual methods or functions.
* Detect defects early.
* Ensure each component works correctly.

### Example

A developer tests the Login Validation method separately before integrating it with the application.

---

# 3. Advantages of Unit Testing

* Detects defects early.
* Simplifies debugging.
* Improves code quality.
* Reduces development cost.

---

# 4. Integration Testing

Integration Testing verifies that multiple modules work correctly when combined.

It focuses on data flow and communication between modules.

### Performed By

* QA Engineers
* Developers

### Example

Testing whether the Login module correctly communicates with the User Database.

---

# 5. Advantages of Integration Testing

* Detects interface issues.
* Ensures modules communicate correctly.
* Identifies integration defects.

---

# 6. System Testing

System Testing verifies the complete integrated application.

The application is tested against business requirements.

### Performed By

* QA Engineers

### Example

Testing an Online Shopping Application:

* Registration
* Login
* Search Products
* Add to Cart
* Payment
* Order Tracking
* Logout

---

# 7. Advantages of System Testing

* Validates the complete application.
* Verifies end-to-end functionality.
* Improves software quality.

---

# 8. User Acceptance Testing (UAT)

User Acceptance Testing (UAT) is the final level of testing.

The client or business users verify whether the application meets their business requirements.

### Performed By

* Client
* End Users
* Product Owner

### Example

A bank verifies whether the Internet Banking application satisfies business needs before production release.

---

# 9. Advantages of UAT

* Confirms business requirements.
* Improves customer satisfaction.
* Reduces production defects.
* Builds confidence before release.

---

# 10. Testing Levels Workflow

```text
Unit Testing
      ↓
Integration Testing
      ↓
System Testing
      ↓
User Acceptance Testing (UAT)
```

---

# 11. Difference Between Testing Levels

| Testing Level | Performed By | Objective |
|--------------|--------------|-----------|
| Unit Testing | Developers | Test individual components |
| Integration Testing | Developers / QA | Test interaction between modules |
| System Testing | QA Engineers | Test the complete application |
| UAT | Client / End Users | Validate business requirements |

---

# 12. Real-Time Example

Suppose your company develops an Online Food Delivery Application.

### Unit Testing

Developers test:

* Login Method
* Payment Method
* Order Calculation

### Integration Testing

QA verifies:

* Login → Database
* Cart → Payment
* Payment → Order History

### System Testing

QA tests the complete application from Registration to Order Delivery.

### User Acceptance Testing

The client verifies whether the application satisfies business requirements before release.

---

# 13. Best Practices

* Complete Unit Testing before Integration Testing.
* Perform Integration Testing before System Testing.
* Execute System Testing thoroughly before UAT.
* Document defects at every level.
* Involve business users during UAT.

---

# 14. Common Mistakes

* Skipping Unit Testing.
* Ignoring Integration defects.
* Starting UAT before System Testing is complete.
* Not involving business users during UAT.

---

# Interview Questions

### 1. What are the four levels of testing?

* Unit Testing
* Integration Testing
* System Testing
* User Acceptance Testing (UAT)

---

### 2. Who performs Unit Testing?

Developers perform Unit Testing.

---

### 3. Who performs System Testing?

QA Engineers perform System Testing.

---

### 4. What is the purpose of UAT?

UAT verifies whether the application meets the client's business requirements before release.

---

### 5. Which testing level is performed first?

Unit Testing.

---

# Key Takeaways

* Software testing is performed at four different levels.
* Each level has a specific objective.
* Defects identified early reduce project cost.
* Following the correct testing order improves software quality.
* UAT is the final validation before production release.
