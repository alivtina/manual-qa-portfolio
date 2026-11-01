# Requirements Traceability Matrix (RTM)

## Objective

This document shows the relationship between requirements
and test cases for a sample e-commerce application.

## Requirements Coverage

| Requirement ID | Requirement | Test Case ID | Coverage Status |
|---|---|---|---|
| REQ-001 | Login with valid credentials | TC-001 | Covered |
| REQ-002 | Add products to the shopping cart | TC-004 | Covered |
| REQ-003 | Complete checkout | TC-002 | Covered |
| REQ-004 | Sort products by price | TC-003 | Covered |
| REQ-005 | Logout | TC-005 | Covered |
| REQ-006 | Remove products from the cart | TC-006 | Covered |
| REQ-007 | Display an error for an incorrect password | N/A | Not Covered |

## Coverage Summary

- Total Requirements: 7
- Covered Requirements: 6
- Not Covered Requirements: 1
- Requirements Coverage: 85.7%

## Coverage Gap

REQ-007 is not covered by an existing test case.

## Recommended Action

Create TC-007 (Login with incorrect password) and
add it to the RTM.

Execute TC-007 to verify that the application displays
an appropriate error message.

## Notes

This is a sample RTM created for QA practice.

The requirements and test case mappings are fictional
and do not represent official SauceDemo requirements.
