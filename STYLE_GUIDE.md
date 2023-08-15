# NEXT CAPTCHA Style Guide

This document outlines the coding and style conventions for contributing to next captcha. Adhering to these conventions ensures consistency and readability across the codebase.

## Table of Contents

- [Coding Standards](#coding-standards)
  - [Indentation](#indentation)
  - [Braces](#braces)
  - [Naming Conventions](#naming-conventions)
- [Documentation](#documentation)
  - [Comments](#comments)
  - [Function/Method Documentation](#functionmethod-documentation)
- [Testing](#testing)
  - [Unit Testing](#unit-testing)
- [Version Control](#version-control)
  - [Commit Messages](#commit-messages)
  - [Branch Naming](#branch-naming)
- [Additional Guidelines](#additional-guidelines)

## Coding Standards

### Indentation

Use **4 spaces** for indentation. Do not use tabs.

### Braces

Use the **Allman style** for braces:

```php
if (condition) {
    // Code block
}
```
### Naming Conventions
- Classes: **PascalCase**
- Methods and functions: **camelCase**
- Variables: **camelCase**
- Constants: **UPPER_CASE**

## Documentation
### Comments
Use meaningful comments to explain complex logic or algorithms. Comments should be concise, clear, and written in English. Avoid excessive commenting for obvious code.

### Function/Method Documentation
Include docblocks for all functions and methods. Use the PHPDoc format for documenting parameters, return types, and descriptions.

```php

/**
 * Calculate and return the sum of two numbers.
 *
 * @param float $num1 The first number.
 * @param float $num2 The second number.
 *
 * @return float The sum of $num1 and $num2.
 */
function calculateSum($num1, $num2) {
    // Implementation
}
```
## Testing
### Unit Testing
Write comprehensive unit tests using a testing framework such as PHPUnit. Ensure that your code passes all tests before submitting a pull request.

## Version Control
### Commit Messages
Write descriptive and concise commit messages that explain the purpose of the changes. Follow the Conventional Commits format for meaningful commit messages.

### Branch Naming
Use descriptive branch names that indicate the purpose of the branch, such as feature/new-captcha-type or fix/issue-description.

## Additional Guidelines
- Keep lines under 80 characters in length.
- Use meaningful variable and function names.
- Follow SOLID principles and maintain clean, modular code.
- Keep dependencies updated using Composer.

By following these guidelines, you contribute to a consistent and high-quality codebase for next CAPTCHA.
