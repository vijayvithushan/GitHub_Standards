# Commit Message Conventions

This document outlines the standard commit message prefixes used in this repository. Using these prefixes helps maintain a clean and readable commit history.

## Standard Prefixes

### Features

- **feat**: A new feature for the user.
  - Example: `feat: add user authentication`

### Bug Fixes

- **fix**: A bug fix.
  - Example: `fix: correct user login error`

### Documentation

- **docs**: Documentation only changes.
  - Example: `docs: update README with setup instructions`

### Code Style

- **style**: Changes that do not affect the meaning of the code (white-space, formatting, missing semi-colons, etc.).
  - Example: `style: format code according to style guide`

### Refactoring

- **refactor**: A code change that neither fixes a bug nor adds a feature.
  - Example: `refactor: improve performance of data processing`

### Performance Improvements

- **perf**: A code change that improves performance.
  - Example: `perf: optimize query performance`

### Tests

- **test**: Adding missing tests or correcting existing tests.
  - Example: `test: add unit tests for user model`

### Chores

- **chore**: Changes to the build process or auxiliary tools and libraries such as documentation generation.
  - Example: `chore: update dependencies`

### Continuous Integration

- **ci**: Changes to your CI configuration files and scripts.
  - Example: `ci: update CircleCI configuration`

### Build System

- **build**: Changes that affect the build system or external dependencies (example scopes: gulp, broccoli, npm).
  - Example: `build: update webpack configuration`

### Reverting Changes

- **revert**: Reverts a previous commit.
  - Example: `revert: revert commit abcdefg`

### Breaking Changes

- **BREAKING CHANGE**: A change that introduces breaking changes.
  - Example: `BREAKING CHANGE: update API to use OAuth`

## Example Commit Messages

Here are some examples of properly formatted commit messages using these prefixes:

- `feat: add new user profile page`
- `fix: resolve issue with user session timeout`
- `docs: add API documentation for user endpoints`
- `style: format code with prettier`
- `refactor: clean up user controller`
- `perf: improve database query performance`
- `test: add tests for user registration`
- `chore: update node dependencies`
- `ci: update TravisCI configuration`
- `build: add babel to project`
- `revert: revert "feat: add new user profile page"`
- `BREAKING CHANGE: update authentication method to OAuth2`

By following these conventions, we ensure that our commit history is easy to understand and maintain.

---

⭐️ From [your-github-username](https://github.com/vijayvithushan)
