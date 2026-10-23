
# Product Listing Test Cases — SauceDemo

**Module:** Product Listing
**Application:** https://www.saucedemo.com/
**Testing Type:** Manual Functional Testing
**Execution Status:** Not Run

## Common Preconditions

- User is logged in as standard_user.
- Products page is displayed.

---

## TC-008 — Verify product listing

**Priority:** High
**Checklist:** CH-008

### Steps
1. Log in with valid credentials.
2. Open the Products page.
3. Observe the product list.

### Expected Result
- Products are displayed.
- Each product is represented by a product card.

---

## TC-009 — Verify product information

**Priority:** High
**Checklist:** CH-009

### Steps
1. Open the Products page.
2. Inspect each product card.

### Expected Result
Each product displays:
- Product name
- Product description
- Product price
- Product image

---

## TC-010 — Sort products A to Z

**Priority:** Medium
**Checklist:** CH-010

### Steps
1. Open the Products page.
2. Select "Name (A to Z)".
3. Observe the product order.

### Expected Result
Products are sorted alphabetically
in ascending order by name.

---

## TC-011 — Sort products Z to A

**Priority:** Medium
**Checklist:** CH-011

### Steps
1. Open the Products page.
2. Select "Name (Z to A)".
3. Observe the product order.

### Expected Result
Products are sorted alphabetically
in descending order by name.

---

## TC-012 — Sort products by price: Low to High

**Priority:** High
**Checklist:** CH-012

### Steps
1. Open the Products page.
2. Select "Price (low to high)".
3. Observe the product prices.

### Expected Result
Products are sorted by price
from lowest to highest.

---

## TC-013 — Sort products by price: High to Low

**Priority:** High
**Checklist:** CH-013

### Steps
1. Open the Products page.
2. Select "Price (high to low)".
3. Observe the product prices.

### Expected Result
Products are sorted by price
from highest to lowest.

---

## TC-014 — Open product details

**Priority:** High
**Checklist:** CH-014

### Steps
1. Open the Products page.
2. Click a product name.

### Expected Result
- Product details page opens.
- Correct product name is displayed.
- Product description is displayed.
- Product price is displayed.
- Product image is displayed.

---

## TC-015 — Return to product listing

**Priority:** Medium
**Checklist:** CH-015

### Steps
1. Open any product details page.
2. Click "Back to products".

### Expected Result
- User returns to the Products page.
- Product listing is displayed.
