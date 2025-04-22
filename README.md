# Project Linting Workflow

This repository includes a GitHub Actions workflow to automatically lint code using Super-Linter.  
It helps maintain consistent code quality and formatting across the project.

## Linting Workflow

- Triggered on push and pull_request events.
- Uses GitHub's Super-Linter.
- Checks all supported file types for formatting and syntax issues.

## Branch Strategy

Development should be done in the **dev** branch.  
Changes should be reviewed and merged into **main** after lint checks pass.
