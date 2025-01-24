# Type 'string[]' is not assignable to type 'string'

This repository contains a demonstration of a common TypeScript error: assigning an array of strings to a variable expecting a single string.  The `bug.ts` file shows the erroneous code, while `bugSolution.ts` provides a corrected version.

## Bug Description

The `greeter` function expects a single string argument. However, the `user` variable is an array of strings. This type mismatch causes a TypeScript compiler error.

## Solution

The solution involves either modifying the `greeter` function to accept an array of strings or modifying the `user` variable to hold a single string. The `bugSolution.ts` file demonstrates the corrected code.