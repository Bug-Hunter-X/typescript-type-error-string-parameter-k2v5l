# TypeScript Type Error: Argument of type 'string[]' is not assignable to parameter of type 'string'

This repository demonstrates a common TypeScript error and its solution. The `bug.ts` file contains code that attempts to pass an array of strings to a function expecting a single string. This results in a type error.

The solution, found in `bugSolution.ts`, addresses this by either modifying the function signature to accept an array or iterating over the array to call the function for each element.