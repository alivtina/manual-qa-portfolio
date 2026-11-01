# Boundary Value Analysis (BVA)

## Overview

Boundary Value Analysis is a test design technique
used to identify defects near the boundaries of valid input ranges.

## Requirement

The Quantity field accepts integer values from 1 to 10 inclusive.

## Test Cases

| ID | Test Value | Expected Result | Description |
|---|---|---|---|
| BVA-001 | 0 | Rejected | Just below minimum |
| BVA-002 | 1 | Accepted | Minimum valid value |
| BVA-003 | 2 | Accepted | Just above minimum |
| BVA-004 | 9 | Accepted | Just below maximum |
| BVA-005 | 10 | Accepted | Maximum valid value |
| BVA-006 | 11 | Rejected | Just above maximum |

## Additional Validation

| ID | Test Value | Expected Result | Description |
|---|---|---|---|
| BVA-007 | 5.5 | Rejected | Non-integer value |

Note: BVA-007 is an additional data type validation check,
not a boundary value test.

## Execution Status

Not Run — these are sample test cases based on fictional requirements.
