# TypeScript Type Error: String to Number

This repository demonstrates a common type error in TypeScript where string values are passed to a function expecting number arguments. The code includes both the erroneous code and a corrected version.

## Bug

The `bug.ts` file contains a function `add` that expects two numbers but is called with two strings. This leads to a type error because TypeScript's type system prevents incompatible type operations.

## Solution

The `bugSolution.ts` file demonstrates how to fix the error by explicitly converting the string arguments to numbers using `parseFloat` or `parseInt` before performing the addition.  This ensures that the `add` function receives number arguments, avoiding the type error.