# .github

Organization profile and default community health files for heisenbug-hq: profile README, issue forms, pull request template, `CONTRIBUTING.md`, `SECURITY.md` and `SUPPORT.md`. Public repo; MIT. Part of Heisenbug (https://heisenbughq.com).

## Hard rules
- These files apply to every repository in the organization that does not define its own. Keep them short and accurate.
- The pull request template is a plain change list: `## Changes` and one bullet. Do not add sections or checklists.
- Text rules: no emojis and no em dashes anywhere.

## Git and pull requests
- Commit at each passing checkpoint and push your feature branch (`type/short-description`). One task, one branch, one pull request.
- Every commit message is exactly one line, a Conventional Commit subject: `type(scope): subject`. No body, no trailers, no `Co-Authored-By`, no tool or session lines.
- Open the pull request with `gh pr create`. The title is one line, a Conventional Commit subject. The description is written like release notes: a short bulleted list of what changed and what is new, in plain user-facing wording. No instructions for the reviewer, no testing notes, no checklist, no list of what you did not do, no generated-by footer.
- Never push to `main` and never force push. Never merge a pull request unless the owner asks you to in this session; then merge only the pull request named, with a squash merge, and never with admin rights or by skipping checks.
- Local hooks in .githooks enforce the commit format and block pushes to main; never bypass them with --no-verify. In a fresh clone run: git config core.hooksPath .githooks
