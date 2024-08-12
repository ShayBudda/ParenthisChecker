# Parenthesis Checker

## Overview
This project includes a method to check if an expression has balanced parentheses using a stack data structure. It supports round `()`, square `[]`, and curly `{}` brackets. The project also includes unit tests to verify the correctness of the implementation.

## Method
### `IsBalanced(string expression)`
- Checks if the given expression has balanced parentheses.
- Returns `true` if balanced, `false` otherwise.

## Unit Tests
The unit tests cover various scenarios, including:
- Single-type brackets
- Mixed-type brackets
- Balanced and unbalanced expressions
- Empty strings

## Challenges
The primary challenge was ensuring that all types of parentheses were correctly matched and nested. Handling edge cases such as an empty string or an expression without any parentheses was also crucial. Using the `Stack` class from the `System.Collections.Generic` namespace made managing the parentheses straightforward.

## Conclusion
This implementation efficiently checks for balanced parentheses using a stack, adhering to the Last-In-First-Out (LIFO) property. The unit tests ensure the method works correctly across different scenarios, providing confidence in its reliability.

## Repository Structure
- `ParenthesisChecker.cs`: Contains the implementation of the `ParenthesisChecker` class.
- `ParenthesisCheckerTests.cs`: Contains the unit tests for the `ParenthesisChecker` class.

