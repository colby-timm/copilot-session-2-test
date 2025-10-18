# Testing Guidelines

## Overview
These guidelines outline the testing principles for this project to ensure code quality and reliability.

## Principles
- All new features must be covered by automated tests.
- Tests should be reliable, maintainable, and fast.
- Use descriptive test names and clear assertions.
- Follow the testing pyramid: prioritize unit tests, supplement with integration and end-to-end (E2E) tests.

## Unit Testing
- Every new feature and code change must include unit tests.
- Unit tests should cover all critical logic, edge cases, and error handling.
- Use Jest as the primary unit testing framework.
- Mock dependencies to isolate the code under test.

## Integration & E2E Testing
- All new features must be validated with integration and E2E tests where applicable.
- Integration tests should verify interactions between components, modules, and APIs.
- E2E tests should simulate real user workflows and validate the system end-to-end.
- Use tools like Jest, Cypress, or Playwright for integration and E2E testing.

## Requirements
- Tests must pass before merging code.
- Code coverage should be monitored and improved over time.
- Flaky tests must be fixed or removed promptly.

## References
- [Jest Documentation](https://jestjs.io/)
- [Cypress Documentation](https://www.cypress.io/)
- [Playwright Documentation](https://playwright.dev/)
