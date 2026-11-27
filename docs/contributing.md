# Contributing to Orbitron

We welcome contributions to Orbitron! Whether you want to report bugs, suggest features, or submit code improvements, this guide will help you get started.

## Table of Contents

- [How to Contribute](#how-to-contribute)
    - [Reporting Bugs](#reporting-bugs)
    - [Suggesting Features](#suggesting-features)
    - [Submitting Code](#submitting-code)
- [Rules](#rules)
    - [Branching Guidelines](#branching-guidelines)
    - [Commit Message Guidelines](#commit-message-guidelines)
    - [Pull Request Guidelines](#pull-request-guidelines)

## How to Contribute

To contribute to Orbitron, follow these steps based on the type of contribution you want to make. Whether you are reporting bugs, suggesting features, or submitting code, this guide will help you navigate the process.

### Reporting Bugs

When you encounter a bug in Orbitron, please provide as much detail as possible to help us understand and reproduce the issue. Include information such as:

- Steps to reproduce the bug
- Expected behavior
- Actual behavior
- Any relevant error messages or logs

You can report bugs by opening an issue on the [GitHub repository](https://github.com/in-orbitron/orbitron/issues).

### Suggesting Features

If you have an idea for a new feature or an improvement to an existing one, please provide a clear and detailed description. Include information such as:

- The problem the feature aims to solve
- How the feature would work
- Any relevant examples or use cases

You can suggest features by opening an issue on the [GitHub repository](https://github.com/in-orbitron/orbitron/issues).

### Submitting Code

When submitting code to Orbitron, please follow these guidelines:

- Fork the repository and create a new branch for your changes.
- Ensure your code follows the project's coding style and conventions.
- Write clear and concise commit messages.
- Include tests for your changes, if applicable.
- Update documentation as needed.

Submit your code by creating a pull request on the [GitHub repository](https://github.com/in-orbitron/orbitron/pulls).

## Rules

When contributing to Orbitron, please adhere to the following rules:

- Be respectful and considerate to other contributors.
- Follow the coding style and conventions used in the project.
- Write clear and concise commit messages.
- Ensure your code is well-documented and tested.
- Avoid making breaking changes without discussion.
- Use the official language of the project, which is English.

### Branching Guidelines

When working on Orbitron, please follow these branching guidelines:

| Branch | Description | Format | Example |
|--------|-------------|--------|---------|
| main   | Stable releases | `main` | `main` |
| develop | Development branch for ongoing work | `develop` | `develop` |
| release | Preparing for a new release | `release/<version>` | `release/1.0.0` |
| feature | New features or improvements | `feature/<issue-number>-<name>` | `feature/123-add-new-feature` |
| bugfix | Fixing bugs | `bugfix/<issue-number>-<name>` | `bugfix/123-fix-issue` |
| hotfix | Urgent fixes for production | `hotfix/<issue-number>-<name>` | `hotfix/123-fix-critical-bug` |
| chore | Routine tasks and maintenance | `chore/<issue-number>-<name>` | `chore/123-update-dependencies` |
| documentation | Updating or improving documentation | `documentation/<issue-number>-<name>` | `documentation/123-update-readme` |
| test | Adding or updating tests | `test/<issue-number>-<name>` | `test/123-add-new-tests` |
| task | General tasks not covered by other categories | `task/<issue-number>-<name>` | `task/123-general-task` |
| refactor | Code refactoring without changing functionality | `refactor/<issue-number>-<name>` | `refactor/123-improve-code-structure` |
| ci | Continuous integration related changes | `ci/<issue-number>-<name>` | `ci/123-update-ci-config` |

### Commit Message Guidelines

When writing commit messages for Orbitron, please follow these guidelines:

| Type | Description | Format | Example |
|------|-------------|--------|---------|
| feat | New feature | `feat: <subject>` | `feat: add login functionality` |
| fix | Bug fix | `fix: <subject>` | `fix: correct login error` |
| docs | Documentation changes | `docs: <subject>` | `docs: update installation instructions` |
| style | Code style changes (formatting, linting, etc.) | `style: <subject>` | `style: apply code formatting` |
| refactor | Code refactoring without changing functionality | `refactor: <subject>` | `refactor: improve code structure` |
| test | Adding or updating tests | `test: <subject>` | `test: add login tests` |
| chore | Routine tasks and maintenance | `chore: <subject>` | `chore: update dependencies` |
| ci | Continuous integration related changes | `ci: <subject>` | `ci: update CI configuration` |
| hotfix | Urgent fixes for production | `hotfix: <subject>` | `hotfix: fix critical login bug` |

### Pull Request Guidelines

When creating a pull request for Orbitron, please follow these guidelines:

1. Ensure your branch is up-to-date with the `develop` branch.
2. Provide a clear and descriptive title for your pull request.
3. Include a detailed description of the changes made and the reason for the changes.
4. Reference any related issues by including `#<issue-number>` in the description.
5. Assign reviewers and labels as appropriate.
6. Ensure all tests pass and the code follows the project's coding standards.
