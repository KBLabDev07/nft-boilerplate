## NFT Boilerplate

This repository includes basic configuration for a code review workflow.

## Code Review Setup

- A GitHub Action (`.github/workflows/super-linter.yml`) runs the GitHub Super Linter on every push and pull request to the `main` branch.
- A pull request template (`.github/PULL_REQUEST_TEMPLATE.md`) reminds contributors to run lint checks and add tests.
- The `CODEOWNERS` file lists `@KBLabDev07` as the default reviewer. Update this handle if you prefer another user.

### Changing the default reviewer

Modify `.github/CODEOWNERS` with your GitHub username (or team) to automatically request reviews on new pull requests.

### Using the pull request template

The template includes a checklist for build validation and documentation updates. Fill it out before requesting a review.

To start collaborating, create a remote repository (e.g., on GitHub) and push this project. Then open pull requests to trigger the workflow.
