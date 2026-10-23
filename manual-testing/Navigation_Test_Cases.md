
# Navigation and Logout Test Cases — SauceDemo

**Module:** Navigation and Logout
**Application:** https://www.saucedemo.com/
**Testing Type:** Manual Functional Testing
**Execution Status:** Not Run

## Common Preconditions

- User is logged in as standard_user.
- Products page is displayed.

---

## TC-035 — Open navigation menu

**Priority:** Medium
**Checklist:** CH-035

### Steps
1. Open the Products page.
2. Click the menu button in the top-left corner.

### Expected Result
- Navigation menu opens.
- Menu items are visible.
- Navigation options are accessible.

---

## TC-036 — Close navigation menu

**Priority:** Medium
**Checklist:** CH-036

### Steps
1. Open the navigation menu.
2. Click the close button (X).

### Expected Result
- Navigation menu closes.
- Products page remains visible.
- User can continue interacting with the page.

---

## TC-037 — Navigate using All Items

**Priority:** Medium
**Checklist:** CH-037

### Steps
1. Open a product details page.
2. Open the navigation menu.
3. Click "All Items".

### Expected Result
- User is redirected to the Products page.
- Product listing is displayed.

---

## TC-038 — Verify About navigation

**Priority:** Medium
**Checklist:** CH-038

### Steps
1. Open the navigation menu.
2. Click "About".

### Expected Result
- User is redirected to the Sauce Labs website.
- The destination page loads successfully.

---

## TC-039 — Logout functionality

**Priority:** High
**Checklist:** CH-039

### Steps
1. Log in with valid credentials.
2. Open the navigation menu.
3. Click "Logout".

### Expected Result
- User is logged out.
- Login page is displayed.
- Products page is no longer accessible
  without authentication.

---

## TC-040 — Access protected page after logout

**Priority:** High
**Checklist:** CH-040

### Steps
1. Log in with valid credentials.
2. Log out using the navigation menu.
3. Enter the following URL in the address bar:
   https://www.saucedemo.com/inventory.html
4. Press Enter.

### Expected Result
- Access to the Products page is denied.
- User is redirected to the login page
  or shown an authentication error.
- Protected product information is not displayed.
