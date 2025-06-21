# NFT Boilerplate

This repository includes basic configuration for a code review workflow.

## Code Review Setup

- A GitHub Action (`.github/workflows/super-linter.yml`) runs the GitHub Super Linter on every push and pull request to the `main` branch.
- A `CODEOWNERS` file automatically requests reviews from the specified user. Replace `@your-github-handle` in `.github/CODEOWNERS` with your GitHub username.
- A pull request template (`.github/PULL_REQUEST_TEMPLATE.md`) reminds contributors to run lint checks and add tests.

To start collaborating, create a remote repository (e.g., on GitHub) and push this project. Then open pull requests to trigger the workflow.
