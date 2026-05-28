# Contributing

Thanks for contributing to this project.

## Development Setup

1. Fork the repository and clone your fork.
2. Install dependencies:

   npm install

3. Start the trigger service locally:

   npm run trigger:start

4. Optional Newman runs:

   npm run test:api
   npm run report
   npm run report:ci

## Branch Naming

Use descriptive branch names:

- feature/<short-name>
- fix/<short-name>
- chore/<short-name>

## Pull Request Guidelines

1. Keep PRs focused and small when possible.
2. Add or update documentation for behavior changes.
3. Include manual validation steps in the PR description.
4. Ensure workflows pass before requesting review.

## Commit Messages

Use clear, action-oriented commit messages. Example:

feat: add project-level history filters

## Code Style

- Keep changes minimal and consistent with existing style.
- Do not commit secrets or environment-specific credentials.
- Validate UI changes in desktop and mobile layout.

## Reporting Bugs

Please use the bug report issue template and include:

- Steps to reproduce
- Expected behavior
- Actual behavior
- Environment details

## Questions

Open a discussion in GitHub Issues with the label `question`.
