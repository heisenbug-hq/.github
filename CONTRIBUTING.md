# Contributing

Heisenbug is pre-release. Outside contributions are not being accepted yet. This file will be updated when they open.

When they do, the working rules are:

- Branch from `main`: `type/short-description`.
- Every commit message is exactly one line, a Conventional Commit subject: `type(scope): subject`. No body and no trailers. Breaking changes use `!`.
- The pull request title is one line, also a Conventional Commit subject. The description is a short bulleted list of what changed and what is new, written like release notes.
- Keep pull requests small and run the repository's check command before opening one.
- Enable the repository hooks once per clone: `git config core.hooksPath .githooks`. They check the commit format and block pushes to `main`.
- No emojis and no em dashes in code, comments, docs or commit messages.

To report a bug or request a feature, use the issue forms. To report a vulnerability, see `SECURITY.md`.
