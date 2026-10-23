
# Checkout Test Cases — SauceDemo

**Module:** Checkout
**Application:** https://www.saucedemo.com/
**Testing Type:** Manual Functional Testing
**Execution Status:** Not Run

## Common Preconditions

- User is logged in as standard_user.
- Shopping cart is empty before each test.
- User has access to the Products page.

## Test Data

Valid customer information:
- First Name: Anna
- Last Name: Test
- Postal Code: 21000

---

## TC-024 — Checkout with valid customer information

**Priority:** High
**Checklist:** CH-024

### Steps
1. Add Sauce Labs Backpack to the cart.
2. Open the shopping cart.
3. Click "Checkout".
4. Enter valid customer information.
5. Click "Continue".

### Expected Result
- Checkout Overview page is displayed.
- No validation errors are shown.
- Order details are visible.

---

## TC-025 — Checkout with empty first name

**Priority:** High
**Checklist:** CH-025

### Steps
1. Add one product to the cart.
2. Open Checkout.
3. Leave First Name empty.
4. Enter Last Name: Test.
5. Enter Postal Code: 21000.
6. Click "Continue".

### Expected Result
- Checkout does not proceed.
- An error message indicates First Name is required.

---

## TC-026 — Checkout with empty last name

**Priority:** High
**Checklist:** CH-026

### Steps
1. Add one product to the cart.
2. Open Checkout.
3. Enter First Name: Anna.
4. Leave Last Name empty.
5. Enter Postal Code: 21000.
6. Click "Continue".

### Expected Result
- Checkout does not proceed.
- An error message indicates Last Name is required.

---

## TC-027 — Checkout with empty postal code

**Priority:** High
**Checklist:** CH-027

### Steps
1. Add one product to the cart.
2. Open Checkout.
3. Enter First Name: Anna.
4. Enter Last Name: Test.
5. Leave Postal Code empty.
6. Click "Continue".

### Expected Result
- Checkout does not proceed.
- An error message indicates Postal Code is required.

---

## TC-028 — Checkout with all fields empty

**Priority:** High
**Checklist:** CH-028

### Steps
1. Add one product to the cart.
2. Open Checkout.
3. Leave all customer information fields empty.
4. Click "Continue".

### Expected Result
- Checkout does not proceed.
- A required-field validation error is displayed.

---

## TC-029 — Verify order summary products

**Priority:** High
**Checklist:** CH-029

### Steps
1. Add Sauce Labs Backpack to the cart.
2. Add Sauce Labs Bike Light to the cart.
3. Open Checkout.
4. Enter valid customer information.
5. Click "Continue".
6. Review the Checkout Overview page.

### Expected Result
- Both selected products are displayed.
- Product names and prices are correct.
- Product quantities are correct.

---

## TC-030 — Verify item total calculation

**Priority:** High
**Checklist:** CH-030

### Steps
1. Add Sauce Labs Backpack ($29.99).
2. Add Sauce Labs Bike Light ($9.99).
3. Proceed to Checkout Overview.
4. Review the Item Total.

### Expected Result
- Item Total equals $39.98.
- Item Total matches the sum of product prices.

---

## TC-031 — Verify tax and total calculation

**Priority:** High
**Checklist:** CH-031

### Steps
1. Add Sauce Labs Backpack ($29.99).
2. Add Sauce Labs Bike Light ($9.99).
3. Proceed to Checkout Overview.
4. Review Item Total, Tax, and Total.

### Expected Result
- Item Total is $39.98.
- Tax is displayed.
- Total equals Item Total plus Tax.
- All amounts are displayed with two decimal places.

---

## TC-032 — Complete order successfully

**Priority:** Critical
**Checklist:** CH-032

### Steps
1. Add one product to the cart.
2. Open Checkout.
3. Enter valid customer information.
4. Click "Continue".
5. Review Checkout Overview.
6. Click "Finish".

### Expected Result
- Order is completed successfully.
- Checkout Complete page is displayed.
- Order confirmation message is visible.

---

## TC-033 — Verify order confirmation page

**Priority:** High
**Checklist:** CH-033

### Steps
1. Complete an order with valid data.
2. Observe the confirmation page.

### Expected Result
- A success confirmation message is displayed.
- A "Back Home" button is available.

---

## TC-034 — Return to products after checkout

**Priority:** Medium
**Checklist:** CH-034

### Steps
1. Complete an order.
2. Click "Back Home".

### Expected Result
- User returns to the Products page.
- Product listing is displayed.
