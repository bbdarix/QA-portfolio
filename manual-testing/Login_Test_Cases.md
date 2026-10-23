
# Login Test Cases — SauceDemo

**Module:** Authentication  
**Application:** https://www.saucedemo.com/  
**Test Type:** Functional Testing  
**Execution Status:** Not Run

---

## TC-001 — Login with valid credentials

**Priority:** High  
**Related Checklist Item:** CH-001

### Preconditions
- User is on the SauceDemo login page.
- Valid test credentials are available.

### Test Data
- Username: standard_user
- Password: secret_sauce

### Test Steps
1. Open https://www.saucedemo.com/
2. Enter `standard_user` in the Username field.
3. Enter `secret_sauce` in the Password field.
4. Click the Login button.

### Expected Result
- User is successfully authenticated.
- The Products page is displayed.
- The URL contains `/inventory.html`.

---

## TC-002 — Login with invalid username

**Priority:** High  
**Related Checklist Item:** CH-002

### Preconditions
- User is on the login page.

### Test Data
- Username: invalid_user
- Password: secret_sauce

### Test Steps
1. Open the login page.
2. Enter `invalid_user` in the Username field.
3. Enter `secret_sauce` in the Password field.
4. Click Login.

### Expected Result
- Login is rejected.
- An error message is displayed.
- User remains on the login page.

---

## TC-003 — Login with invalid password

**Priority:** High  
**Related Checklist Item:** CH-003

### Test Data
- Username: standard_user
- Password: wrong_password

### Test Steps
1. Open the login page.
2. Enter `standard_user`.
3. Enter `wrong_password`.
4. Click Login.

### Expected Result
- Login is rejected.
- An error message is displayed.
- User remains on the login page.

---

## TC-004 — Login with empty username

**Priority:** Medium  
**Related Checklist Item:** CH-004

### Test Data
- Username: empty
- Password: secret_sauce

### Test Steps
1. Open the login page.
2. Leave Username empty.
3. Enter `secret_sauce` in Password.
4. Click Login.

### Expected Result
- Login is rejected.
- An error indicating that the username is required is displayed.

---

## TC-005 — Login with empty password

**Priority:** Medium  
**Related Checklist Item:** CH-005

### Test Data
- Username: standard_user
- Password: empty

### Test Steps
1. Open the login page.
2. Enter `standard_user`.
3. Leave Password empty.
4. Click Login.

### Expected Result
- Login is rejected.
- An error indicating that the password is required is displayed.

---

## TC-006 — Login with both fields empty

**Priority:** Medium  
**Related Checklist Item:** CH-006

### Test Steps
1. Open the login page.
2. Leave Username empty.
3. Leave Password empty.
4. Click Login.

### Expected Result
- Login is rejected.
- A validation error is displayed.
- User remains on the login page.

---

## TC-007 — Login with locked-out user

**Priority:** High  
**Related Checklist Item:** CH-007

### Test Data
- Username: locked_out_user
- Password: secret_sauce

### Test Steps
1. Open the login page.
2. Enter `locked_out_user`.
3. Enter `secret_sauce`.
4. Click Login.

### Expected Result
- Login is rejected.
- A message indicates that the user is locked out.
- User remains on the login page.
