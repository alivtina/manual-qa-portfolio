# Authentication Test Cases

## Overview

This document contains sample manual test cases for login and registration functionality of a fictional e-commerce application.

The test cases are based on predefined training requirements and have not been executed against a real application.

## Test Cases

### TC-001: Login with Valid Credentials

**Test Case ID:** TC-001

**Objective:** Verify that a registered user can log in using valid credentials.

**Preconditions:**
1. The user is registered in the system.
2. The user has a valid email address and password.
3. The user is on the Login page.

**Test Data:**
- Email: `testuser@example.com`
- Password: `ValidPass123!`

**Steps to Reproduce:**
1. Enter the registered email address in the Email field.
2. Enter the correct password in the Password field.
3. Click the Login button.

**Expected Result:**
- The user is successfully authenticated.
- The user gains access to their account.

**Execution Status:** Not Run

---

### TC-002: Login with Incorrect Password

**Test Case ID:** TC-002

**Objective:** Verify that a user cannot log in using an incorrect password.

**Preconditions:**
1. The user is registered in the system.
2. The user is on the Login page.

**Test Data:**
- Email: `testuser@example.com`
- Password: `WrongPass123!`

**Steps to Reproduce:**
1. Enter the registered email address in the Email field.
2. Enter an incorrect password in the Password field.
3. Click the Login button.

**Expected Result:**
- The user is not authenticated.
- An appropriate error message is displayed.
- The user cannot access their account.

**Execution Status:** Not Run

---

### TC-003: Registration with a Password Shorter Than 8 Characters

**Test Case ID:** TC-003

**Objective:** Verify that a user cannot register with a password containing fewer than 8 characters.

**Preconditions:**
1. The user is on the Registration page.
2. A valid, unregistered email address is available.

**Test Data:**
- Email: `newuser@example.com`
- Password: `Test123` (7 characters)

**Steps to Reproduce:**
1. Enter the unregistered email address in the Email field.
2. Enter `Test123` in the Password field.
3. Click the Register button.

**Expected Result:**
- Registration is rejected.
- No user account is created with the provided credentials.

**Execution Status:** Not Run
