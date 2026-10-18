# GitHub Rulesets Practice

A beginner-friendly repository to learn and test GitHub Rulesets, branch protection, and pull request workflows.

## Goals

- Understand how GitHub Rulesets work.
- Protect the `main` branch from direct changes.
- Practice feature branches and pull requests.
- Prevent force pushes and accidental branch deletion.
- Learn how to enforce code quality checks before merging.

## Branch Strategy

| Branch | Purpose |
|---|---|
| `main` | Contains approved changes |
| `feature/update-readme` | Practice README updates |
| `feature/test-ruleset` | Test GitHub Ruleset restrictions |

## Ruleset Configuration

The following rules will be tested on the `main` branch:

- Require a pull request before merging.
- Block force pushes.
- Restrict branch deletion.
- Explore required approvals.
- Explore required status checks.

**Note:** These rules must be configured in GitHub repository settings. Listing them here does not automatically enable them.

## Practice Tasks

- [ ] Add and commit this README.
- [ ] Create a branch named `feature/update-readme`.
- [ ] Make a change to this file.
- [ ] Push the feature branch to GitHub.
- [ ] Open a pull request into `main`.
- [ ] Test whether direct pushes to `main` are blocked.
- [ ] Test whether force pushes are blocked.
- [ ] Explore required status checks.

## Basic Git Commands

Check repository status:

```bash
git status
```

Create a feature branch:

```bash
git switch -c feature/update-readme
```

Stage and commit changes:

```bash
git add README.md
git commit -m "Update README"
```

Push the branch:

```bash
git push -u origin feature/update-readme
```

## Learning Resources

- [GitHub Rulesets Documentation](https://docs.github.com/en/repositories/configuring-branches-and-merges-in-your-repository/managing-rulesets)
- [GitHub Pull Request Documentation](https://docs.github.com/en/pull-requests)

## Purpose

This repository is for learning, experimentation, and understanding how repository rules help protect code and maintain a safer development workflow.
