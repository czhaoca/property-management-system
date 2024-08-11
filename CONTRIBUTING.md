# Contributing to Property Management System

We're excited that you're interested in contributing to the Property Management System! This document outlines the process for contributing to this project.

## Code of Conduct

By participating in this project, you are expected to uphold our Code of Conduct, which promotes a respectful and inclusive environment for all contributors.

## How to Contribute

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes in your branch.
4. Ensure your code adheres to the existing style (see `docs/development/coding_standards.md`).
5. Run the tests and make sure they all pass (see `docs/development/testing_strategy.md`).
6. Write or update tests for your changes.
7. Update the documentation if necessary (see the Documentation section below).
8. Commit your changes and push your branch to your fork.
9. Submit a pull request to the main repository.

## Pull Request Process

1. Ensure any install or build dependencies are removed before the end of the layer when doing a build.
2. Update the README.md and relevant documentation with details of changes to the interface, this includes new environment variables, exposed ports, useful file locations and container parameters.
3. Increase the version numbers in any examples files and the README.md to the new version that this Pull Request would represent.
4. You may merge the Pull Request in once you have the sign-off of two other developers, or if you do not have permission to do that, you may request the second reviewer to merge it for you.

## Reporting Bugs

1. Check the GitHub Issues to ensure the bug hasn't already been reported.
2. If you're unable to find an open issue addressing the problem, open a new one.
3. Include a title and clear description, as much relevant information as possible, and a code sample or an executable test case demonstrating the expected behavior that is not occurring.

## Suggesting Enhancements

1. Check the GitHub Issues to ensure the enhancement hasn't already been suggested.
2. Open a new issue with a clear title and detailed description of the suggested enhancement.
3. Include any relevant examples or mockups if applicable.

## Documentation

When contributing, please update the documentation accordingly. Our documentation is structured as follows:

- `docs/requirements/`: Update functional or non-functional requirements if your contribution affects them.
- `docs/design/`: Update system architecture, database schema, or UI mockups if your changes impact the design.
- `docs/api/`: Update API documentation for any changes to the API.
- `docs/user_guides/`: Update admin or tenant guides if your changes affect user interactions.
- `docs/development/`: Update setup guide, coding standards, or testing strategy as necessary.
- `docs/deployment/`: Update deployment guide or maintenance procedures if your changes affect these processes.

## Styleguides

### Git Commit Messages

* Use the present tense ("Add feature" not "Added feature")
* Use the imperative mood ("Move cursor to..." not "Moves cursor to...")
* Limit the first line to 72 characters or less
* Reference issues and pull requests liberally after the first line

### JavaScript Styleguide

* All JavaScript must adhere to [JavaScript Standard Style](https://standardjs.com/).

### TypeScript Styleguide

* All TypeScript must adhere to [TypeScript ESLint Rules](https://github.com/typescript-eslint/typescript-eslint/tree/master/packages/eslint-plugin).

### Documentation Styleguide

* Use [Markdown](https://daringfireball.net/projects/markdown/) for documentation.
* Follow the existing structure in the `docs/` directory.

## Development Process

1. Check the project board for open issues or feature requests.
2. Assign yourself to an issue or create a new one for the feature you want to work on.
3. Create a new branch for your work.
4. Develop and test your changes locally.
5. Ensure your changes adhere to the coding standards and pass all tests.
6. Update documentation as necessary.
7. Submit a pull request for review.

For more details on the development process, please refer to `docs/development/setup_guide.md`.

## License

By contributing to the Property Management System, you agree that your contributions will be licensed under its GNU Affero General Public License v3.0 (AGPL-3.0).