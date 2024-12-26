This repository demonstrates a common error in TypeScript when handling optional parameters that can be either strings or null.  The issue arises when an undefined value is passed to a function expecting a string or null. This README provides steps to reproduce the issue and a solution.

**Steps to reproduce:**

1. Clone this repository.
2. Open `bug.ts`.
3. Run the TypeScript code using a compiler like tsc.
4. Observe the compiler error that occurs.

**Solution:**

The solution is to either explicitly check for undefined and handle it appropriately, or change the function to accept undefined values.

Review the corrected code in `bugSolution.ts` for a working example.