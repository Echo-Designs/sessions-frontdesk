# sessions-frontdesk agent brief

Sessions Retreat's Front Desk Playbook, a training page for desk staff served by GitHub Pages. One of the Echo hotel operating system's tools (D21 in `Echo-Designs/echo-os/docs/DECISIONS.md`). The program's rules in that repo's `CLAUDE.md` apply here too.

## Rules

1. This repository is the source of truth for the published site. Every change is a branch and a pull request; publish only committed content.
2. This repository is public, because it serves a GitHub Pages site. Nothing goes in it that may not be read by anyone: no secret value or secret name, no account identifier, no internal path, no guest data. It has no secrets.
3. A merge to `main` republishes the site. `docs/OPERATIONS.md` and the changelog in `docs/PROJECT-STATUS.md` are updated in the same pull request as the change they describe, and a change to the site adds a `docs/DEPLOY-LOG.md` entry.
4. Hotel-specific values on the page are listed in `docs/OPERATIONS.md`.
5. Never force-push, rewrite history, or delete a repository or branch. Nothing live changes until this tool's cut-over is recorded in the echo-os register.
6. No em dashes or en dashes in anything written here.
7. When a rule is unclear, ask in the session and continue.

## Reading order

`docs/OPERATIONS.md`, then `docs/PROJECT-STATUS.md`, then the site files.
