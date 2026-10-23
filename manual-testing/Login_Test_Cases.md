
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
| Passed | 7 |
| Failed | 0 |
| Blocked | 0 |
| Not Run | 0 |
| Execution Progress | 100% |
| Pass Rate | 100% |

## 2. Test Execution Results

| Test Case ID | Test Scenario | Status | Actual Result |
|---|---|---|---|
| TC-001 | Login with valid credentials | PASS | User successfully logged in |
| TC-002 | Login with invalid username | PASS | Login rejected and error displayed |
| TC-003 | Login with invalid password | PASS | Login rejected and error displayed |
| TC-004 | Login with empty username | PASS | Username validation error displayed |
| TC-005 | Login with empty password | PASS | Password validation error displayed |
| TC-006 | Login with both fields empty | PASS | Login rejected and validation error displayed |
| TC-007 | Login with locked-out user | PASS | Login rejected and error message displayed |

## 3. Defect Summary

No defects were identified during the executed login tests.

## 4. Observations

- Valid credentials allowed successful authentication.
- Invalid credentials were rejected.
- Required-field validation worked as expected.
- The locked-out user was unable to log in.
- An error message was displayed for the locked-out user.

## 5. Conclusion

All seven planned login test cases were executed.

All tests passed.

No functional defects were identified in the tested scenarios.

The Login module testing is complete within the defined scope.

## 6. Next Steps

- Execute Product Listing tests.
- Verify product sorting functionality.
- Verify product details and navigation.
- Document test execution results.
