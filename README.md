# Type Error in TypeScript Function
This repository demonstrates a common type error in TypeScript and its solution.

## Bug
The `greet` function expects a `string` for the `date` parameter. However, the function call provides a `Date` object. This causes a type error.

## Solution
The solution involves changing the parameter type to `Date` to correctly match the function call.