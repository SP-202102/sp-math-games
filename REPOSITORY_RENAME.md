# Repository Rename Guidance

This repository was renamed from 'little_math_games' to 'sp-math-games' on 2026-03-08 18:06:12 +01:00.

## Existing Clones

1. Save or commit local work before pulling the rename changes.
2. Update your remote URL: git remote set-url origin https://github.com/SP-202102/sp-math-games.git
3. Fetch and fast-forward: git fetch origin --prune; git pull --ff-only
4. Optionally rename your local clone folder after you leave the repo directory.

## Rollback

- Backup ZIP: D:\Develop\GitHub\sp-repo-renamer\artifacts\little_math_games-to-sp-math-games-20260308-161119\little_math_games-to-sp-math-games-20260308-161119-backup.zip
- Safety tag: pre-repo-rename/little_math_games-to-sp-math-games-20260308-161119
- Restore the ZIP into a separate folder or reset to the safety tag before pushing if you need a full rollback.

## Review Notes

- Secrets were skipped by default; inspect skipped files manually when needed.
- Review CI, badges, registries, and other repo-coupled integrations before pushing.
