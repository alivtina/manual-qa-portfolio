# Registration Test Scenarios

## Overview

This document contains sample test scenarios for the registration
functionality of a fictional e-commerce application.

The scenarios are based on training requirements and have not
been executed against a real application.

## Requirements

- Email is required.
- Password is required.
- Password must contain at least 8 characters.
- Email must have a valid format.
- Users cannot register with an already registered email address.

## Test Scenarios

| ID | Test Scenario | Type |
|---|---|---|
| TS-001 | Verify that a user cannot register without providing an email address. | Negative |
| TS-002 | Verify that a user cannot register without providing a password. | Negative |
| TS-003 | Verify that a user cannot register with a password containing fewer than 8 characters. | Negative |
| TS-004 | Verify that a user cannot register using an email address with an invalid format. | Negative |
| TS-005 | Verify that a user cannot register using an email address that is already registered. | Negative |
| TS-006 | Verify that a user can register using a valid, unique email address and a password containing at least 8 characters. | Positive |
