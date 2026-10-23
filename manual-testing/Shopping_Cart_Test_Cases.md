
# Shopping Cart Test Cases — SauceDemo

**Module:** Shopping Cart
**Application:** https://www.saucedemo.com/
**Testing Type:** Manual Functional Testing
**Execution Status:** Not Run

## Common Preconditions

- User is logged in as standard_user.
- Shopping cart is empty.
- Products page is displayed.

---

## TC-016 — Add one product to cart

**Priority:** High
**Checklist:** CH-016

### Steps
1. Open the Products page.
2. Click "Add to cart" for Sauce Labs Backpack.
3. Open the shopping cart.

### Expected Result
- The product is added to the cart.
- The correct product name and price are displayed.
- Cart badge displays 1.

---

## TC-017 — Add multiple products to cart

**Priority:** High
**Checklist:** CH-017

### Steps
1. Open the Products page.
2. Add Sauce Labs Backpack to cart.
3. Add Sauce Labs Bike Light to cart.
4. Open the shopping cart.

### Expected Result
- Both products are displayed in the cart.
- Product names and prices are correct.
- Cart badge displays 2.

---

## TC-018 — Verify cart badge count

**Priority:** High
**Checklist:** CH-018

### Steps
1. Add one product to cart.
2. Observe the cart badge.
3. Add another product.
4. Observe the cart badge again.

### Expected Result
- Badge displays 1 after adding the first product.
- Badge displays 2 after adding the second product.

---

## TC-019 — Remove product from cart

**Priority:** High
**Checklist:** CH-019

### Steps
1. Add two products to cart.
2. Open the shopping cart.
3. Click "Remove" for one product.

### Expected Result
- The selected product is removed.
- The other product remains in the cart.
- Cart badge displays 1.

---

## TC-020 — Verify badge after removing all products

**Priority:** Medium
**Checklist:** CH-020

### Steps
1. Add one product to cart.
2. Open the shopping cart.
3. Click "Remove".
4. Observe the cart badge.

### Expected Result
- The product is removed.
- The cart is empty.
- The cart badge is no longer displayed.

---

## TC-021 — Verify product details in cart

**Priority:** High
**Checklist:** CH-021

### Steps
1. Add Sauce Labs Backpack to cart.
2. Open the shopping cart.
3. Inspect the product information.

### Expected Result
- Correct product name is displayed.
- Correct product description is displayed.
- Correct product price is displayed.
- Quantity is 1.

---

## TC-022 — Verify cart persistence during navigation

**Priority:** High
**Checklist:** CH-022

### Steps
1. Add two products to cart.
2. Open the shopping cart.
3. Click "Continue Shopping".
4. Open a product details page.
5. Return to the Products page.
6. Open the shopping cart again.

### Expected Result
- Both products remain in the cart.
- Product details are unchanged.
- Cart badge displays 2.

---

## TC-023 — Open checkout from shopping cart

**Priority:** High
**Checklist:** CH-023

### Steps
1. Add one product to cart.
2. Open the shopping cart.
3. Click "Checkout".

### Expected Result
- Checkout information page opens.
- First Name field is displayed.
- Last Name field is displayed.
- Postal Code field is displayed.
- Continue button is available.
