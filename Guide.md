# Contribution Guide

Welcome to the Project-Drone repository! This guide explains how a group of contributors (up to 5 people) can collaborate efficiently using our branching and pull request workflow.

## Branch Structure

- **main**: The production branch. Only stable, reviewed code is merged here.
- **test**: The integration branch. All feature branches are merged here first for testing and review before merging into `main`.

## Contribution Workflow

1. **Branching**
   - Never commit directly to `main` or `test`.
   - To start work on a new feature or fix, create a new branch from either `main` or `test` (preferably from `test`).
   - Name your branch after the feature or fix you are working on. Example: `feature-login`, `bugfix-camera`.

2. **Development**
   - Make your changes in your feature branch.
   - Commit often with clear messages.

3. **Pull Requests**
   - When your work is ready, open a Pull Request (PR) to merge your feature branch into `test`.
   - Assign reviewers from your team.
   - Address any feedback and make necessary changes.

4. **Merging**
   - Only after successful review and testing, your PR will be merged into `test`.
   - Periodically, the `test` branch will be merged into `main` by a maintainer after final review.

## Rules

- **No direct commits** to `main` or `test`.
- **Always use Pull Requests** for merging any branch into `test`.
- **Branch naming**: Use descriptive names based on the feature or fix.
- **Code review**: At least one team member should review your PR before merging.
- **Sync regularly**: Pull the latest changes from `test` before starting new work to avoid conflicts.

## Example Workflow

1. Pull the latest changes from `test`:
   ```sh
   git checkout test
   git pull origin test
   ```
2. Create your feature branch:
   ```sh
   git checkout -b feature-awesome
   ```
3. Work on your changes, commit, and push:
   ```sh
   git add .
   git commit -m "Add awesome feature"
   git push origin feature-awesome
   ```
4. Open a PR to merge `feature-awesome` into `test`.
5. After review and approval, your branch will be merged into `test`.
6. Maintainers will periodically merge `test` into `main`.

## Tips

- Communicate with your team to avoid duplicate work.
- Keep your branches up to date with `test`.
- Write clear commit messages and PR descriptions.

