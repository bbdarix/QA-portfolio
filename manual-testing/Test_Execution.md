
# Test Execution Report — SauceDemo

**Project:** SauceDemo (Swag Labs)
**Module:** Login / Authentication
**Testing Type:** Manual Functional Testing
**Environment:** Google Chrome / Windows
**Execution Date:** 2026-10-23
**Tested By:** QA Portfolio Author

## 1. Test Execution Summary

| Metric | Result |
|---|---|
| Total Test Cases | 7 |
| Passed | 6 |
| Failed | 0 |
| Blocked | 0 |
| Not Run | 1 |
| Execution Progress | 85.7% |
| Pass Rate (Executed Tests) | 100% |

## 2. Test Execution Results

| Test Case ID | Test Scenario | Status | Actual Result |
|---|---|---|---|
| TC-001 | Login with valid credentials | PASS | User successfully logged in |
| TC-002 | Login with invalid username | PASS | Login rejected and error displayed |
| TC-003 | Login with invalid password | PASS | Login rejected and error displayed |
| TC-004 | Login with empty username | PASS | Username validation error displayed |
| TC-005 | Login with empty password | PASS | Password validation error displayed |
| TC-006 | Login with both fields empty | PASS | Login rejected and validation error displayed |
| TC-007 | Login with locked-out user | NOT RUN | Not executed |

## 3. Defect Summary

No defects were identified during the executed login tests.

## 4. Observations

- Valid credentials allowed successful authentication.
- Invalid credentials were rejected.
- Required-field validation worked as expected.
- The locked-out user scenario remains untested.

## 5. Conclusion

Six out of seven planned login test cases were
executed successfully.

No failures were observed in the executed tests.

Login module testing is not yet complete because
TC-007 remains unexecuted.

## 6. Next Steps

- Execute TC-007 (locked-out user).
- Update the execution results.
- Continue testing the Product Listing module.
