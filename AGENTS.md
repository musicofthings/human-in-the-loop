# AGENTS.md

## Cursor Cloud specific instructions

This repository is **configuration/documentation only**. It contains:

- `README.md` — describes the repo.
- `slack-community.json` — Slack community configuration for `#all-human-in-the-loop`.

There is **no application code, no dependencies, no build system, no test suite, and no runnable services**. There is nothing to install and no dev server to start.

The only meaningful validation is checking that `slack-community.json` is valid JSON. Both `jq` and `python3` are available:

- `jq . slack-community.json`
- `python3 -m json.tool slack-community.json`
