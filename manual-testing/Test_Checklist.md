
# Test Checklist — SauceDemo

**Project:** SauceDemo (Swag Labs)  
**Application:** https://www.saucedemo.com/  
**Testing Type:** Manual Functional Testing  
**Status:** Not Executed

## 1. Login

- [ ] CH-001 Verify login with valid credentials
- [ ] CH-002 Verify login with invalid username
- [ ] CH-003 Verify login with invalid password
- [ ] CH-004 Verify login with empty username
- [ ] CH-005 Verify login with empty password
- [ ] CH-006 Verify login with both fields empty
- [ ] CH-007 Verify login with a locked-out user

## 2. Product Listing

- [ ] CH-008 Verify products are displayed after login
- [ ] CH-009 Verify each product has a name, description, price, and image
- [ ] CH-010 Verify sorting by name (A to Z)
- [ ] CH-011 Verify sorting by name (Z to A)
- [ ] CH-012 Verify sorting by price (low to high)
- [ ] CH-013 Verify sorting by price (high to low)
- [ ] CH-014 Verify product details open when clicking a product name
- [ ] CH-015 Verify navigation back to the product list

## 3. Shopping Cart

- [ ] CH-016 Verify adding one product to the cart
- [ ] CH-017 Verify adding multiple products to the cart
- [ ] CH-018 Verify the cart badge displays the correct item count
- [ ] CH-019 Verify removing a product from the cart
- [ ] CH-020 Verify the cart badge updates after removing a product
- [ ] CH-021 Verify product details in the cart
- [ ] CH-022 Verify the cart remains populated when navigating between pages
- [ ] CH-023 Verify checkout can be opened from the cart

## 4. Checkout

- [ ] CH-024 Verify checkout with valid customer information
- [ ] CH-025 Verify checkout with empty first name
- [ ] CH-026 Verify checkout with empty last name
- [ ] CH-027 Verify checkout with empty postal code
- [ ] CH-028 Verify checkout with all fields empty
- [ ] CH-029 Verify order summary displays correct products
- [ ] CH-030 Verify item total calculation
- [ ] CH-031 Verify tax and total calculation
- [ ] CH-032 Verify order can be completed successfully
- [ ] CH-033 Verify the confirmation page is displayed
- [ ] CH-034 Verify returning to the product list after order completion

## 5. Navigation and Logout

- [ ] CH-035 Verify the navigation menu opens
- [ ] CH-036 Verify the navigation menu closes
- [ ] CH-037 Verify the All Items navigation option
- [ ] CH-038 Verify the About navigation option
- [ ] CH-039 Verify logout functionality
- [ ] CH-040 Verify access to protected pages after logout
