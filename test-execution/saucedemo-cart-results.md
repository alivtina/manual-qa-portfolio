# SauceDemo Shopping Cart Test Execution

## Overview

Manual functional testing of the shopping cart
on the SauceDemo demo e-commerce application.

Application: https://www.saucedemo.com/
Execution Method: Manual

## TC-003 — Add Product to Shopping Cart

**Preconditions:**
- User is logged in as standard_user.
- Products page is displayed.
- Shopping cart is empty.

**Test Steps:**
1. Find Sauce Labs Backpack on the Products page.
2. Click Add to cart.
3. Check the shopping cart badge.
4. Open the shopping cart.
5. Verify that Sauce Labs Backpack is displayed.

**Expected Result:**
Sauce Labs Backpack is added to the shopping cart.
The cart badge displays 1, and the product is visible
on the cart page.

**Actual Result:**
Sauce Labs Backpack was successfully added to the shopping cart.
The cart badge displayed 1, and the product was visible
on the cart page.

**Status:** PASS

## Test Execution Summary

| Total Tests | Passed | Failed |
|---|---|---|
| 1 | 1 | 0 |

## Notes

This test was manually executed against the SauceDemo
web application.
