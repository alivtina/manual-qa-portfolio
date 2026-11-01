# Equivalence Partitioning (EP)

## Overview

Equivalence Partitioning is a test design technique that divides
input data into groups expected to behave similarly.

A representative value is selected from each equivalence class
to reduce the number of tests while maintaining useful coverage.

## Requirement

The Age field accepts integer values from 18 to 65 inclusive.

## Equivalence Classes

| ID | Equivalence Class | Test Value | Expected Result |
|---|---|---|---|
| EP-001 | Integers below the valid range | 17 | Rejected |
| EP-002 | Integers within the valid range | 25 | Accepted |
| EP-003 | Integers above the valid range | 66 | Rejected |
| EP-004 | Non-integer values | 25.5 | Rejected |

## Test Design Notes

Values 25 and 30 belong to the same valid equivalence class.

Under basic Equivalence Partitioning, testing both values is
not necessary because the expected behavior is the same.

Additional tests may be required if there are other business
rules or suspected defects.

## Execution Status

Not Run — these are sample test cases based on fictional requirements.
