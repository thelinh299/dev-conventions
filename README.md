# Dev Conventions

> A central reference for commit message conventions, branch naming rules, and Git workflow best practices used by our development team.

## 📌 Purpose

This repository documents and standardizes our GitHub collaboration practices to ensure clarity, consistency, and effective team communication.

By following these conventions, we:
- Improve code traceability
- Enable automation (e.g., changelogs, semantic release)
- Onboard new developers faster
- Avoid unnecessary Git conflicts and confusion

## 📂 Contents

- [`commit-message-guidelines.md`](./commit-message-guidelines.md)  
  Guidelines for writing clear, consistent commit messages based on the Conventional Commits standard.

- [`branch-naming-guidelines.md`](./branch-naming-guidelines.md)  
  Recommended branch naming formats by type and purpose.

- [PR Template Example](./.github/PULL_REQUEST_TEMPLATE.md) *(optional)*  
  Pull Request template you can add to any repo.

## ✅ Quick Start

Follow these steps in every project:

1. Name your branch like this:
   ```
   feat/123-add-login-api
   fix/456-crash-on-profile-load
   ```

2. Write commits like:
   ```
   feat(auth): implement login with JWT

   fix(api): return correct status code on failure
   ```

3. Link issues in commit or PR footers:
   ```
   Closes #123
   ```

## 💡 Recommended Tools

- [`commitlint`](https://github.com/conventional-changelog/commitlint) – enforce commit format
- [`semantic-release`](https://github.com/semantic-release/semantic-release) – auto changelog & versioning
- Pre-commit Git hooks (e.g. Husky or lint-staged)

---

> Keep this repo updated as our team standards evolve. PRs welcome!
