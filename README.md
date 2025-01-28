# Hack Type Inference Bug

This repository demonstrates a subtle type inference bug in Hack related to function overloading. The provided `bug.hack` file contains Hack code that can trigger this issue under specific circumstances. The `bugSolution.hack` file offers a potential solution.  This issue highlights the importance of clear type annotations, especially in situations involving function overloading to avoid ambiguity for the Hack compiler.

**How to Reproduce:**

1. Clone this repository.
2. Compile and run `bug.hack` using the Hack compiler.
3. Observe any compiler errors or unexpected behavior. (A solution is included to see the correct implementation)

**Understanding the Problem:**

The core problem stems from potential ambiguity in how the Hack compiler infers the type of `x` across multiple function calls. This issue is more likely to manifest when working with larger codebases or more complicated scenarios of function overloading, which is why it might be considered 'uncommon'.