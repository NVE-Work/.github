# Contributing Guide

## Issue Creation
- Always create an issue for new features, bugs, or improvements.
- Use labels like `type: feature`, `type: bug`, `priority: P0/P1/P2`, and `size: XS-S-M-L-XL`.

## Branching
- Branch off `main` or `develop` (depending on project).
- Branch naming: `feature/issue-<issue_number>-short-description`
- Example: `feature/issue-21-influencer-pages`

## Workflow
- Every issue = 1 branch = 1 PR.
- No direct commits to `main` branch.
- Code must go through **Pull Request** with at least 1 code reviewer approval.
- Use linked issues (`Closes #issue_number`) in PRs.

## Code Style
- Follow existing coding style.
- Use Prettier/ESLint where applicable.

## Pull Requests
- Title: `[Feature] Short Description`
- Must link the corresponding issue.
- Complete the checklist in PR template.

## Merging Rules
- Only **admins/maintainers** can merge into `main`.
- Squash commits preferred.
