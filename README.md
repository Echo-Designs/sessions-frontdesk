# sessions-frontdesk

Sessions Retreat's Front Desk Playbook: one training page for desk staff (late checkout, early check-in, one more night, suggestions, how to charge it in Cloudbeds, food and drink, price list), served by GitHub Pages. The prices on it are read from Cloudbeds when the page is built; the page itself reads and writes nothing.

Part of the Echo hotel operating system. Program home, decisions and the tools register: `Echo-Designs/echo-os`. Read `CLAUDE.md` first.

This repository is public because it serves a GitHub Pages site. Everything committed here can be read by anyone; `_config.yml` keeps the documents off the published site.

## Repo tree

```
sessions-frontdesk/
  README.md               this file
  CLAUDE.md               binding rules for sessions in this repo
  docs/PROJECT-STATUS.md  the tracking log: one changelog entry per session, current state
  docs/BACKLOG.md         designed work not yet scheduled
  docs/TECH-DEBT.md       deferred fixes, TD-NN
  docs/OPERATIONS.md      how it runs: what it shows, where it is built, how it is published
  docs/DEPLOY-LOG.md      one entry per publish
  _config.yml             Pages exclude list: keeps the documents off the published site
  index.html              the page, as published
  assets/                 logo and the three Cloudbeds screenshots
  robots.txt              keeps search engines out
```

The site stays at the repository root rather than under `src/`, because GitHub Pages serves it from there.

## Where does X live

| Fact | Lives in |
|---|---|
| What changed, in which session | `docs/PROJECT-STATUS.md` section 1 |
| Current state | `docs/PROJECT-STATUS.md` section 2 |
| How it is built and published, and its address | `docs/OPERATIONS.md` |
| Hotel-specific values on the page | `docs/OPERATIONS.md`, Hotel-specific values |
| Each publish and its verification | `docs/DEPLOY-LOG.md` |
| Deferred fixes | `docs/TECH-DEBT.md` |
| Designed work not yet scheduled | `docs/BACKLOG.md` |
| Program decisions, the board, the register | `Echo-Designs/echo-os` |

## Read in this order

1. `CLAUDE.md`
2. `docs/OPERATIONS.md`
3. `docs/PROJECT-STATUS.md`
