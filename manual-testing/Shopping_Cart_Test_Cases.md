
# Test Execution Report — SauceDemo

**Project:** SauceDemo (Swag Labs)  
**Testing Type:** Manual Functional Testing  
**Environment:** Google Chrome / Windows  
**Execution Period:** October 2026  
**Status:** In Progress

## 1. Test Execution Summary

| Metric | Result |
|---|---|
| Total Test Cases Executed | 23 |
| Passed | 23 |
| Failed | 0 |
| Blocked | 0 |
| Pass Rate (Executed Tests) | 100% |

## 2. Login Module

| Test Case ID | Test Scenario | Status |
|---|---|---|
| TC-001 | Login with valid credentials | PASS |
| TC-002 | Login with invalid username | PASS |
| TC-003 | Login with invalid password | PASS |
| TC-004 | Login with empty username | PASS |
| TC-005 | Login with empty password | PASS |
| TC-006 | Login with both fields empty | PASS |
| TC-007 | Login with locked-out user | PASS |

**Result:** 7/7 PASS

## 3. Product Listing Module

| Test Case ID | Test Scenario | Status |
|---|---|---|
| TC-008 | Verify product listing | PASS |
| TC-009 | Verify product information | PASS |
| TC-010 | Sort products A to Z | PASS |
| TC-011 | Sort products Z to A | PASS |
| TC-012 | Sort by price: Low to High | PASS |
| TC-013 | Sort by price: High to Low | PASS |
| TC-014 | Open product details | PASS |
| TC-015 | Return to product listing | PASS |

**Result:** 8/8 PASS

## 4. Shopping Cart Module

| Test Case ID | Test Scenario | Status |
|---|---|---|
| TC-016 | Add one product to cart | PASS |
| TC-017 | Add multiple products to cart | PASS |
| TC-018 | Verify cart badge count | PASS |
| TC-019 | Remove product from cart | PASS |
| TC-020 | Remove all products | PASS |
| TC-021 | Verify product details in cart | PASS |
| TC-022 | Verify cart persistence | PASS |
| TC-023 | Open checkout | PASS |

**Result:** 8/8 PASS

## 5. Defect Summary

No functional defects were identified in the
23 executed test cases.

## 6. Overall Assessment

| Module | Status |
|---|---|
| Login | Completed |
| Product Listing | Completed |
| Shopping Cart | Completed |
| Checkout | Not Started |
| Navigation and Logout | Not Started |

All 23 executed test cases passed.

Testing is ongoing. The application has not
yet been fully evaluated against the test plan.

## 7. Next Steps

1. Create and execute Checkout test cases.
2. Verify form validation and order calculations.
3. Test order completion.
4. Continue with Navigation and Logout testing.
5. Prepare the final Test Summary Report.
