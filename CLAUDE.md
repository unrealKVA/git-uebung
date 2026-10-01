# CLAUDE.md

## Git workflow rules

- **Always work on a feature branch.** Before making changes, create or switch to a branch (e.g. `feature/<short-description>`).
- **Never commit directly to `main`.** All changes reach `main` via a pull request.
- **Never push without approval.** Before any `git push`, show the full `git diff origin/main..HEAD` of what will be pushed and wait for explicit approval.
- **Write commit messages in English.**
- **Never commit secrets or `.env` files.** This includes API keys, tokens, passwords, credentials and any `.env*` files. Check staged files before every commit.
