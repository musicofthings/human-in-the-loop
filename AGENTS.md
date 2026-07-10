# human-in-the-loop

## Cursor Cloud specific instructions

This is a **configuration/data-only repository**. It contains no application code, build
system, package manager, dependencies, services, or automated tests. The entire repo is:

- `README.md` — describes the repo purpose.
- `slack-community.json` — declares the `#all-human-in-the-loop` Slack channel config.

There is nothing to install, build, run, or serve. No update/startup script is required.

The only meaningful validation is confirming `slack-community.json` is well-formed JSON:

```bash
python3 -m json.tool slack-community.json > /dev/null && echo "valid JSON"
```
