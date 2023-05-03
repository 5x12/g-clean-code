## Table of Contents

- [Introduction](#introduction)
- [Variables](docs/variables.md)
  - Variable names should reveal intent
  - Use meaningful and pronounceable variable names
  - Use the same vocabulary for the same type of variable
  - Avoid magic numbers and magic strings
  - Use variables to keep code "DRY" ("Don't Repeat Yourself")
  - Use explanatory variables
  - Avoid mental mapping
  - Don't add unneeded context
- [Dispensables](docs/dispensables.md)
  - Avoid comments
  - Remove dead code
  - Avoid print statements (even glorified print statements such as df.head(), df.describe(), df.plot())
- [Functions](docs/functions.md)
  - Use functions to keep code "DRY"
  - Functions should do one thing
  - Functions should only be one level of abstraction
  - Function names should say what they do
  - Use type hints to improve readability
  - Avoid side effects
  - Avoid unexpected side effects on values passed as function parameters
  - Function arguments (2 or fewer ideally)
  - Use default arguments instead of short circuiting or conditionals
  - Don't use flags as function parameters

## Introduction

Clean code practices (from [Clean Code](https://www.amazon.com/Clean-Code-Handbook-Software-Craftsmanship/dp/0132350882) and [Refactoring](https://www.amazon.com/Refactoring-Improving-Existing-Addison-Wesley-Signature/dp/0134757599)) adapted for machine learning / data science workflows in Python. This is not a style guide. It's a guide to producing readable, reusable, and refactorable software.


Targets Python3.7+
