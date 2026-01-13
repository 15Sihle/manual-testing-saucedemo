# Checkout Page Test Cases – SauceDemo

## Preconditions
- User is logged in with valid credentials
- At least one product is added to the cart

---

## Checkout Test Cases

| Test Case ID | Test Scenario | Test Steps | Expected Result | Status |
|-------------|--------------|------------|-----------------|--------|
| TC_CHECKOUT_01 | Navigate to checkout | 1. Add product to cart<br>2. Click cart icon<br>3. Click Checkout | User is redirected to checkout information page | Pass |
| TC_CHECKOUT_02 | Submit checkout with valid information | 1. Enter First Name<br>2. Enter Last Name<br>3. Enter Postal Code<br>4. Click Continue | User is redirected to checkout overview page | Pass |
| TC_CHECKOUT_03 | Submit checkout with empty fields | 1. Leave all fields empty<br>2. Click Continue | Error message is displayed | Pass |
| TC_CHECKOUT_04 | Submit checkout with missing postal code | 1. Enter First Name<br>2. Enter Last Name<br>3. Leave Postal Code empty<br>4. Click Continue | Error message is displayed | Pass |
| TC_CHECKOUT_05 | Verify product details on overview page | 1. Proceed to checkout overview | Correct product name, price, and quantity displayed | Pass |
| TC_CHECKOUT_06 | Complete checkout | 1. Click Finish | Order confirmation message is displayed | Pass |
| TC_CHECKOUT_07 | Cancel checkout | 1. Click Cancel during checkout | User is redirected back to Products page | Pass |
| TC_CHECKOUT_08 | Verify total price calculation | 1. Add product to cart<br>2. Proceed to overview page | Item total, tax, and total price are calculated correctly | Pass |


