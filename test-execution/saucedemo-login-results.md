# SauceDemo Login Test Execution

## Overview

Manual testing of the login functionality
on the SauceDemo demo e-commerce application.

Application: https://www.saucedemo.com/
Test Type: Functional Testing
Execution Method: Manual

## TC-001 — Login with Valid Credentials

**Precondition:** User is on the login page.

**Test Data:**
- Username: standard_user
- Password: secret_sauce

**Steps:**
1. Open the SauceDemo login page.
2. Enter the valid username.
3. Enter the valid password.
4. Click Login.

**Expected Result:**
User successfully logs in and can access the application.

**Actual Result:**
User successfully logged in.

**Status:** PASS

---

## TC-002 — Login with Incorrect Password

**Precondition:** User is on the login page.

**Test Data:**
- Username: standard_user
- Password: wrong_password

**Steps:**
1. Open the SauceDemo login page.
2. Enter the valid username.
3. Enter the incorrect password.
4. Click Login.

**Expected Result:**
Login is rejected, an error message is displayed,
and the user cannot access the application.

**Actual Result:**
Login was rejected. The following error message appeared:

"Epic sadface: Username and password do not match any user in this service"

**Status:** PASS

---

## Test Execution Summary

| Total Tests | Passed | Failed |
|---|---|---|
| 2 | 2 | 0 |

## Notes

Both tests were manually executed against the SauceDemo
web application.
