# Product Page Test Cases – SauceDemo

## Preconditions
- User is logged in with valid credentials
- User is on the Products page

---

## Product Page Test Cases

| Test Case ID | Test Scenario | Test Steps | Expected Result | Status |
|-------------|--------------|------------|-----------------|--------|
| TC_PROD_01 | Products list is displayed | 1. Login with valid credentials | All products are displayed on the Products page | Pass |
| TC_PROD_02 | Product name is visible | 1. Login<br>2. View product list | Each product has a visible name | Pass |
| TC_PROD_03 | Product price is visible | 1. Login<br>2. View product list | Each product displays a price | Pass |
| TC_PROD_04 | Add product to cart | 1. Login<br>2. Click “Add to cart” on a product | Product is added to the cart | Pass |
| TC_PROD_05 | Remove product from cart | 1. Add product to cart<br>2. Click “Remove” | Product is removed from the cart | Pass |
| TC_PROD_06 | Cart icon updates | 1. Add product to cart | Cart icon shows item count | Pass |
| TC_PROD_07 | Sort products by price (low to high) | 1. Select sort option | Products are sorted correctly | Pass |
| TC_PROD_08 | Product image is clickable | 1. Click on product image | User is redirected to product details page | Pass |


