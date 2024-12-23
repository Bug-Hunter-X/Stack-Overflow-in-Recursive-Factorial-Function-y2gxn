# Stack Overflow in Recursive Factorial Function

This repository demonstrates a common error in recursive functions: stack overflow. The `foo` function calculates the factorial of a number using recursion.  For large inputs, the recursive calls consume too much stack space, leading to a stack overflow error. The solution demonstrates how to mitigate this by using iterative approach or adding tail-call optimization (if supported by the compiler).
