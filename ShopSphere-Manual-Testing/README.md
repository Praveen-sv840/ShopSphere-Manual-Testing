# ShopSphere – Manual Testing Project

## Project Overview

This project focuses on performing manual testing on an e-commerce web application using different software testing techniques.

The objective is to verify application functionality, identify defects, execute test cases, and document testing results.

**Application:** [Practice Software Testing](https://practicesoftwaretesting.com/)

**Testing Type:** Manual Testing

## Project Objectives

- Understand the application and its functionalities.
- Identify test scenarios for different modules.
- Design positive and negative test cases.
- Execute test cases and record actual results.
- Identify, document, and report defects.
- Perform retesting and regression testing.
- Prepare a test execution report.

## Modules Covered

1. User Registration
2. Login
3. Product Search
4. Shopping Cart
5. Coupon Application
6. Checkout and Payment

## Testing Techniques Used

- Boundary Value Analysis
- Equivalence Partitioning
- Decision Table Testing
- State Transition Testing
- Positive Testing
- Negative Testing
- Black Box Testing

## Project Structure

```text
ShopSphere-Manual-Testing/
│
├── README.md
│
├── Test-Scenarios.xlsx
│
├── Test-Cases.xlsx
│
├── Bug-Reports.xlsx
│
├── Screenshots/
│
└── Test-Execution-Report.md
```

## Project Deliverables

| File | Description |
|---|---|
| README.md | Project overview and documentation |
| Test-Scenarios.xlsx | Contains identified test scenarios and priorities |
| Test-Cases.xlsx | Contains test cases, preconditions, steps, test data, expected results, actual results, and execution status |
| Bug-Reports.xlsx | Contains identified defects, reproduction steps, expected and actual results, severity, and priority |
| Screenshots/ | Contains screenshots captured during testing |
| Test-Execution-Report.md | Summarizes test execution results and overall testing activities |

## Test Execution Summary

A total of 29 test cases were considered during the testing cycle.

| Execution Status | Count |
|---|---:|
| Total Test Cases | 29 |
| Passed | 18 |
| Failed | 6 |
| Blocked | 5 |
| Not Executed | 0 |

**Pass Percentage:** 62.07%

**Fail Percentage:** 20.69%

**Blocked Percentage:** 17.24%

## Defect Summary

A total of 6 defects were documented during testing.

| Severity | Count |
|---|---:|
| Major | 2 |
| Medium | 4 |
| Total | 6 |

### Defects Identified

| Bug ID | Module | Description | Severity | Priority |
|---|---|---|---|---|
| BUG-001 | Login & Registration | Password validation accepts a 6-character minimum instead of the expected 8-character minimum | Medium | P2 |
| BUG-002 | Product Search | Product search does not return relevant results for one- or two-character search terms | Medium | P2 |
| BUG-003 | Shopping Cart | Cart subtotal and total are recalculated after an invalid decimal quantity is entered | Medium | P2 |
| BUG-004 | Checkout & Payment | Checkout allows the user to proceed when the Country field is empty | Major | P1 |
| BUG-005 | Checkout & Payment | Bank Transfer accepts a numeric value in the Account Name field | Major | P1 |
| BUG-006 | Checkout & Payment | Credit Card payment displays a blank validation error message | Medium | P2 |

## Testing Process

The following activities were performed as part of the manual testing process:

1. Application Understanding – Explored the application and identified its modules.
2. Test Scenario Preparation – Identified functionalities that needed testing.
3. Test Case Design – Prepared test cases with preconditions, test steps, test data, and expected results.
4. Test Execution – Executed test cases and recorded actual results.
5. Defect Reporting – Documented failed scenarios with reproduction steps, severity, and priority.
6. Retesting – Verify reported defects after developers provide fixes.
7. Regression Testing – Verify that existing functionalities continue to work after changes.
8. Test Execution Reporting – Summarize overall testing results.

## Testing Conclusion

Manual testing was performed on the ShopSphere e-commerce application to verify its major functionalities.

A total of 29 test cases were considered, out of which 18 passed, 6 failed, and 5 were blocked.

Six defects were documented, including two major-severity defects and four medium-severity defects.

The failed test cases require investigation and defect resolution. The blocked test cases require further attention before testing can be completed.

Retesting and regression testing should be performed after the defects are fixed.

---

**Project:** ShopSphere – Manual Testing

**Testing Type:** Functional Manual Testing
