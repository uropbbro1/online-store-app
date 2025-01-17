# Contributing to online-store-app

## Branching Strategy

*   `main`: Production-ready code.
*   `develop`: Integration branch for new features and bug fixes.
*   `feature/*`: Feature branches (e.g., `feature/user-authentication`).
*   `bugfix/*`: Bug fix branches (e.g., `bugfix/payment-error`).

## Pull Request (PR) Process

1.  Create a new branch for each feature or bug fix.
2.  Make your changes and commit them with clear messages.
3.  Push your branch to GitHub.
4.  Create a pull request from your branch to the `develop` branch.
5.  Request reviews from at least two team members.
6.  Address all feedback and make necessary changes.
7.  Once approved, merge your PR into the `develop` branch.

## Commit Messages

Use clear, concise commit messages following this format: `<type>(<scope>): <subject>`.

*   **type:** `feat`, `fix`, `docs`, `test`, `refactor`, `chore`, etc.
*   **scope:**  A brief description of what the commit affects (e.g., `user-authentication`, `payment`).
*   **subject:** A concise summary of the changes.

**Example:** `feat(user-authentication): Implement password reset functionality.`

## Code Reviews

*   Code reviews are mandatory for all pull requests.
*   Check for code quality, adherence to coding standards, and potential bugs.
*   Provide constructive feedback.

## Coding Standards

*   **Coding Style:** Follow [PEP 8](https://peps.python.org/pep-0008/) (or relevant style guide for your language).
*   **Documentation:** Document all public classes and functions.
*   **Testing:** Write unit tests for all new code.
