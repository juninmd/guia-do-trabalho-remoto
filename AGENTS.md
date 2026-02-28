```markdown
# AGENTS.md File Guidelines

These guidelines are designed to ensure the consistent, high-quality development of the AGENTS.md repository. Adherence to these principles is mandatory for all code development.

## 1. DRY (Don't Repeat Yourself)

*   All functions, classes, and methods should have single, well-defined purposes.
*   Avoid duplication of logic and code across multiple files.
*   Refactor whenever possible to eliminate redundant code.
*   When a feature is implemented, it should be a new module or component instead of duplicating functionality.

## 2. KISS (Keep It Simple, Stupid)

*   Code should be as concise and easy to understand as possible.
*   Favor simple solutions over complex ones.
*   Use clear and descriptive names for variables, functions, and classes.
*   Limit the complexity of each module.

## 3. SOLID Principles

*   **Single Responsibility Principle:** Each class/module should have one, and only one, reason to change.
*   **Open/Closed Principle:** Classes/modules should be open for extension but closed for modification.
*   **Liskov Substitution Principle:**  Subclasses should be substitutable for their base classes without altering the correctness of the program.
*   **Interface Segregation Principle:** Clients should not be forced to satisfy contracts they do not need.
*   **Dependency Inversion Principle:** High-level modules should not depend on low-level modules.

## 4. YAGNI (You Aren't Gonna Need It)

*   Implement only what is absolutely required for the current task.
*   Avoid adding features or functionality that are not currently needed.
*   Refactor to remove unnecessary code that wasn't originally required.

## 5. Code Structure & File Layout

*   Each file should have a clear and logical structure.
*   Use appropriate naming conventions (e.g., camelCase, snake\_case).
*   Include comments to explain complex logic or decisions.
*   Organize code logically.  Follow a consistent directory structure.
*   Ensure comments clearly state *why* code is written, not just *what* it does.
*   Maintain a consistent indentation style.
*   Use docstrings to explain the purpose, inputs, and outputs of functions and classes.

## 6.  Coding Standards & Style

*   Use a consistent code style (e.g., follow PEP 8).
*   Use a code formatter (e.g., Black, yapf) to enforce formatting rules.
*   Employ a linter to automatically identify potential issues.
*   Standardize code formatting across the codebase.

## 7.  Testing - Mocks Only**

*   All unit tests must be written using mocks and stubs.
*   Mocks should be implemented to cover core functionality and expected behavior.
*   Tests should verify the correct output of functions and classes, not their internal state.
*   Test coverage should aim for at least 80% using automated testing frameworks.
*   Tests must be independent and fail fast.
*   Do not include any external dependencies beyond the required mocks.

## 8.  Code Length Constraints

*   The total lines of code in all files should not exceed 180 lines.
*   Code should be readable and well-formatted.
*   Break down large functions into smaller, more manageable units.

## 9.  Development Workflow

*   Start with a clear understanding of requirements.
*   Write tests early and often.
*   Conduct regular code reviews.
*   Continuously refactor and improve the codebase.
*   Prioritize code quality and maintainability.

## 10.  Documentation

*   Include API documentation for all functions and classes.
*   Document the purpose and usage of each module and class.
*   Provide examples to illustrate how to use the code.
```