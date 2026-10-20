# Enhancements — Standalone Edition Changelog

Upstream: https://github.com/mattpocock/skills
Maintainer of this edition: Syed Mujtaba Abbas (@mujtbabbas)

## v1.1.0 — Enhancement release (2026-10-20)
- Added "About This Standalone Edition" section to README.md with upstream link, base version provenance, and credit.
- Added this changelog (ENHANCEMENTS.md).
- Added .github/dependabot.yml (weekly GitHub Actions updates, plus npm for the root package.json, which carries the changesets release tooling).
- Added .markdownlint.json and .github/workflows/markdown-check.yml (markdown linting automation for the skill documentation; upstream needs-info.yml, release.yml and triage-label.yml workflows kept as-is).
- Added .editorconfig (standard editor settings: UTF-8, LF, 2-space indent).

## v1.0.0 — Baseline (2026-10-20)
- Clean standalone baseline of mattpocock/skills at upstream release v1.3.1 (snapshot commit 5beb35b040e3de97e54fa9e386d7e42d15c295c2, upstream HEAD dated 2026-10-19).
- Fork history severed; all files and the MIT licence (LICENSE) preserved as-is.
- Note: upstream ships AGENTS.md as a symlink to CLAUDE.md — preserved as a symlink in this baseline; a connector snapshot push cannot carry symlinks, so it will need a non-connector route or a real copy at push time.
