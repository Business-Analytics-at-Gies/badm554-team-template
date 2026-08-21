# Course rules for AI assistants in this repository

This is a BADM 554 team project repository. AI assistance with git is welcome for everyday operations: staging, committing, pushing, pulling, reading diffs, writing `.gitignore` entries, and generating commit permalinks.

## Never run these unsupervised

Do **not** run, and do not suggest running without an explicit human decision first:

- `git push --force` (any force push)
- `git reset --hard`
- `git clean -fd`
- `git checkout .` / `git restore .` on unstaged work
- `git rebase`
- `git branch -D`
- `git filter-branch` / `git filter-repo`
- any git command containing `-f` or `--force` that the user did not explicitly ask for

These are the operations where a confident wrong move destroys work unrecoverably. If one of them seems necessary, stop and tell the user to ask in the course tech-support forum first.

**For learners:** AI can drive git. You keep your hand on the parking brake. If an assistant proposes a command with `force`, `hard`, or `-f` in it, stop and ask in the forum.

## Other repository rules

- Never commit credentials, personal data exports, or another person's information. Respect the `.gitignore`.
- Until Module 6: each teammate commits only inside their own `members/<netid>/` folder; `shared/` is read-only.
- Never rewrite `docs/ai-attribution-log.md` history — append only.
