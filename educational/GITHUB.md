# GitHub Repo Reference — unusual-activity-test

**URL:** https://github.com/aidatadeveloper/unusual-activity-test
**Visibility:** public
**Standard:** ~/.claude/educational/GITHUB_PROJECT_STANDARD.md

## What this is

Static HTML/JS test fixture for the optionsdatabase.com unusual-activity screener. Includes DAILY/, datepicker test screenshots, and JSON data files (hormuz_oil, oil_prices).

## What's gitignored

Per the standard at `~/.claude/educational/GITHUB_PROJECT_STANDARD.md`:
- Secrets: `.env`, `**/credentials*`, `**/*.pem`, `**/*.key`, `**/*.token`, `**/*.secret`, `**/tokens.json`
- Python: `__pycache__/`, `.venv/`, `*.pyc`
- Node: `node_modules/`
- Logs: `logs/`, `*.log`
- OS / editor: `Thumbs.db`, `.DS_Store`, `.vscode/`, `.idea/`
- Claude Code per-user cache: `.claude/`

## Common workflow

```bash
git add <files>
git commit -m "<imperative summary>"
git push origin main
```
