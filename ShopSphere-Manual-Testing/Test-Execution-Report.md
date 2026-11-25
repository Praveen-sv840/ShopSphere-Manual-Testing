# ShopSphere – Test Execution Report

## 1. Project Information

| Field | Details |
|---|---|
| Project Name | ShopSphere |
| Application | E-commerce web application |
| Testing Type | Manual Testing |
| Test Cycle | Cycle 1 |
| Test Environment | FireFox Browser – Ubuntu |
| Application URL | https://practicesoftwaretesting.com |
| Report Status | Sample report – illustrative data |

## 2. Testing Objective

The objective of this testing activity is to verify that the main ShopSphere e-commerce workflows work as expected, identify defects, and record the results of test execution.

## 3. Testing Scope

The following modules are included in this sample report:

- Registration And Login
- Product Search
- Shopping Cart
- Coupon Application
- Checkout and Payment

**Note:** Only modules and scenarios actually covered by the test cycle should be included in a real project report.

## 4. Test Environment

| Component | Configuration |
|---|---|
| Application | ShopSphere / Practice Software Testing |
| Testing Type | Manual |
| Browser | FireFox |
| Operating System | Ubuntu |
| Device | Desktop |
| Test Data | Valid and invalid sample user credentials and product data |

## 5. Test Execution Summary

The following figures are illustrative examples for learning purposes.

| Execution Status | Number of Test Cases |
|---|---:|
| Total Test Cases | 29 |
| Passed | 18 |
| Failed | 6 |
| Blocked | 5 |
| Not Executed | 0 |

**Pass Percentage:** (Passed Test Cases / Executed Test Cases) × 100

**Pass Percentage:** (18 / 29) × 100 = **62.07%**

**Fail Percentage:** (6 / 29) × 100 = **20.69%**

**Blocked Percentage:** (5 / 29) × 100 = **17.24%**

## 6. Test Execution Details

| Test Case ID | Module | Test Description | Expected Result | Actual Result | Status |
|---|---|---|---|---|---|
| TC-001 | Registration | Register with valid details | Account should be created | Account created successfully | Pass |
| TC-002 | Registration | Register with an already registered email | Appropriate error should appear | Error message displayed | Pass |
| TC-003 | Login | Login with valid credentials | User should log in successfully | Login successful | Pass |
| TC-004 | Login | Login with an incorrect password | Error message should appear | Error message displayed | Pass |
| TC-005 | Login | Submit login form with empty email | Email validation should appear | Validation message not displayed | Fail |
| TC-006 | Search | Search for an existing product | Matching products should appear | Matching products displayed | Pass |
| TC-007 | Search | Search for a non-existing product | No-results message should appear | No-results message not displayed | Fail |
| TC-008 | Product Details | Open a product | Correct product details should appear | Product details displayed | Pass |
| TC-009 | Cart | Add a product to the cart | Product should be added | Product added successfully | Pass |
| TC-010 | Cart | Update product quantity | Cart quantity and total should update | Cart total did not update correctly | Fail |
| TC-011 | Checkout | Continue checkout with required details | Checkout should proceed | Checkout proceeded | Pass |
| TC-012 | Checkout | Submit checkout with a required field empty | Validation should appear | Validation not displayed | Fail |
| TC-013 | Order Confirmation | Complete an order | Confirmation should be displayed | Confirmation displayed | Pass |
| TC-014 | Cart | Remove a product from the cart | Product should be removed | Product remained in cart | Fail |
| TC-015 | Login | Submit login form with empty password | Password validation should appear | Validation not displayed | Fail |

**Note:** These are sample execution records, not verified results from the live application. Replace them with your actual test results. The remaining test cases are represented in the overall summary only.

## 7. Failed Test Cases

| Test Case ID | Module | Defect Description | Status |
|---|---|---|---|
| TC-005 | Login | Email validation message not displayed | Fail |
| TC-007 | Search | No-results message not displayed | Fail |
| TC-010 | Cart | Cart total does not update correctly | Fail |
| TC-012 | Checkout | Required-field validation not displayed | Fail |
| TC-014 | Cart | Removed product remains in cart | Fail |
| TC-015 | Login | Password validation message not displayed | Fail |

## 8. Defect Summary

The following is an illustrative defect distribution.

| Severity | Number of Defects |
|---|---:|
| Critical | 0 |
| Major | 2 |
| Medium | 3 |
| Minor | 1 |
| **Total** | **6** |

Severity and priority are different: severity describes the impact of a defect, while priority describes how urgently it should be fixed. Record the actual severity and priority in the bug report.


## 9. Testing Conclusion

Based on the illustrative execution summary, 30 test cases were considered executed: 24 passed and 6 failed, resulting in an 80% pass rate.

Six sample defects were identified and recorded for investigation. The failed scenarios should be fixed and retested. Regression testing should also be performed on related modules after the fixes.

**Sample recommendation:** Do not consider the application ready for release based only on this sample report. Make the release decision after reviewing actual test results, defect severity, unresolved issues, and the agreed acceptance criteria.


