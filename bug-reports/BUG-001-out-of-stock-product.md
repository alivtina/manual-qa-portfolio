# BUG-001: Out-of-Stock Product Can Be Added to Cart

**Type:** Sample Bug Report (Training Scenario)

**Status:** Not Reported

**Severity:** Major

**Priority:** High

**Environment:** Fictional e-commerce web application

## Requirement

Users must not be able to add out-of-stock products to the shopping cart.

## Preconditions

1. The application is accessible.
2. A product marked as "Out of Stock" exists.

## Steps to Reproduce

1. Open the product page of an out-of-stock item.
2. Observe the "Add to Cart" button.
3. Click the "Add to Cart" button.
4. Open the shopping cart.

## Expected Result

The out-of-stock product must not be added to the shopping cart.

## Actual Result (Simulated)

The "Add to Cart" button is active, and the out-of-stock
product is successfully added to the shopping cart.

## Impact

The defect violates the inventory availability requirement
and may lead to orders containing unavailable products.

## Notes

This is a sample bug report based on a fictional training
scenario. The defect has not been reproduced in a real application.
