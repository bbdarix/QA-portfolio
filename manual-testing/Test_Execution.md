
# Test Execution Report — SauceDemo

**Project:** SauceDemo (Swag Labs)  
**Testing Type:** Manual Functional Testing  
**Environment:** Google Chrome / Windows  
**Execution Period:** October 2026  
**Status:** In Progress

## 1. Test Execution Summary

| Metric | Result |
|---|---|
| Total Executed | 34 |
| Passed | 34 |
| Failed | 0 |
| Blocked | 0 |
| Pass Rate | 100% |

## 2. Module Results

| Module | Total | Passed | Failed | Status |
|---|---|---|---|---|
| Login | 7 | 7 | 0 | Completed |
| Product Listing | 8 | 8 | 0 | Completed |
| Shopping Cart | 8 | 8 | 0 | Completed |
| Checkout | 11 | 11 | 0 | Completed |
| Navigation | 6 | 0 | 0 | Not Started |

## 3. Checkout Execution Details

| Test ID | Scenario | Status |
|---|---|---|
| TC-024 | Valid checkout information | PASS |
| TC-025 | Empty first name | PASS |
| TC-026 | Empty last name | PASS |
| TC-027 | Empty postal code | PASS |
| TC-028 | All fields empty | PASS |
| TC-029 | Order summary products | PASS |
| TC-030 | Item total calculation | PASS |
| TC-031 | Tax and total calculation | PASS |
| TC-032 | Complete order | PASS |
| TC-033 | Order confirmation | PASS |
| TC-034 | Return to products | PASS |

## 4. Observations

### OBS-001 — Checkout validation behavior

**Related Test Case:** TC-028

When all customer information fields are empty,
the application displays an error indicating
that the First Name field is required.

The checkout process does not proceed.

**Assessment:** Expected behavior according to
the documented test case.

**Final Status:** PASS

## 5. Defect Summary

No confirmed functional defects were identified
during the 34 executed test cases.

## 6. Overall Assessment

Four functional modules have been tested.

All executed test cases passed.

Navigation and Logout testing remains outstanding.

## 7. Next Steps

1. Create Navigation and Logout test cases.
2. Execute the remaining six tests.
3. Document execution results.
4. Prepare the final Test Summary Report.
