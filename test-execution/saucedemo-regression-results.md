# SauceDemo Regression Test Execution

## Overview

Manual regression testing of authentication
and session management functionality.

Application: https://www.saucedemo.com/
Execution Method: Manual

## REG-003 — Verify Logout and Protected Page Access

**Preconditions:**
- User has valid SauceDemo credentials.
- User can access the Products page after login.

**Test Steps:**
1. Log in using standard_user and secret_sauce.
2. Navigate to the Products page.
3. Copy the Products page URL.
4. Log out of the application.
5. Open the copied Products page URL directly.

**Expected Result:**
After logout, the user cannot access the protected
Products page using its direct URL.

The application redirects the user to Login
or displays an access-denied message.

**Actual Result:**
The application displayed the following error message:

"Epic sadface: You can only access '/inventory.html' when you are logged in."

Access to the Products page was denied.

**Status:** PASS

## Test Execution Summary

| Total Tests | Passed | Failed |
|---|---|---|
| 1 | 1 | 0 |

## Notes

This test was manually executed against SauceDemo.

The test checks protected page access after logout.
It does not constitute a complete security assessment.

No specific bug fix was verified as part of this execution.
