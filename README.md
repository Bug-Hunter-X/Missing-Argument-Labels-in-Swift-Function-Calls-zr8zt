# Missing Argument Labels in Swift Function Calls

This repository demonstrates a common error in Swift: forgetting to include argument labels when calling a function that defines them.

## The Bug
The Swift compiler strictly enforces argument labels for function parameters when those labels are defined.  Omitting the label when calling the function results in a compiler error.  This can lead to difficulties in debugging and understanding code behavior.

## The Solution
Ensure that you always include the argument labels when calling functions. The labels improve code readability and prevent this type of error.

## How to Reproduce
1. Clone this repository.
2. Open the `bug.swift` file. 
3. Run the code. Observe the compiler error related to the missing argument label.
4. Open the `bugSolution.swift` file to see the corrected code.