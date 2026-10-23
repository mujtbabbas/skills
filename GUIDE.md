# Reader's Guide — skills (Matt Pocock's Skills For Real Engineers)

## What this project is

**Skills For Real Engineers** is Matt Pocock's personal collection of
**agent skills he uses every day to do real engineering — "not vibe
coding."** Where heavyweight agent frameworks (the README names approaches
like GSD, BMAD and Spec-Kit) take control of your process away, these skills
are deliberately **small, easy to adapt and composable**, work with any model,
and encode decades of engineering experience. They exist to fix four classic
agent failure modes the README calls out: the agent didn't do what you wanted,
the agent is way too verbose, the code doesn't work, and the codebase becomes
a ball of mud.

## How the content is organised

- `skills/` — the skills themselves, grouped by area, each skill in its own
  folder with a `SKILL.md`:
  - `skills/engineering/` — the daily code-work set: `ask-matt`,
    `code-review`, `codebase-design`, `diagnosing-bugs`, `domain-modeling`,
    `grill-with-docs`, `implement`, `implement-spec`,
    `improve-codebase-architecture`, `pr`, `prototype`, `research`, `retro`,
    `setup-matt-pocock-skills`, `tdd`, `to-spec`, `to-tickets`, `triage`,
    `wayfinder`, `wizard`.
  - `skills/productivity/` — `grill-me`, `grilling`, `handoff`, `teach`,
    `to-questionnaire`, `wait-what`, `writing-for-agents`.
  - `skills/misc/` — `git-guardrails-claude-code`, `migrate-to-shoehorn`,
    `scaffold-exercises`, `setup-pre-commit`.
  - `skills/in-progress/` and `skills/deprecated/` — works in progress and
    retired skills, kept visible on purpose.
- [`README.md`](README.md) — the front door: the 30-second installation, the
  "Why These Skills Exist" rationale, and the **Reference**, which explains
  the key design rule — *user-invoked* skills (typed by you, e.g. `/grill-me`)
  orchestrate, while *model-invoked* skills hold reusable discipline the agent
  can reach for itself.
- `docs/` — documentation; `scripts/` — repo tooling; `SCOPE.md` and
  `.out-of-scope/` — what belongs in the collection and what does not;
  `GLOSSARY.md` — shared terminology; `AGENTS.md`/`CLAUDE.md` — instructions
  for agents working in this repo.

## How to use it

1. Follow the README's **Installation (30-second setup)**: fetch the skills,
   then run `/setup-matt-pocock-skills`.
2. Browse the **Reference** by area (Engineering first for most developers)
   and invoke skills by name in your agent session.
3. Adapt them — the project explicitly invites you to hack around and make
   them your own.

## About this standalone edition

This repository is a standalone edition of
[mattpocock/skills](https://github.com/mattpocock/skills), converted from a
fork into its own repository and enhanced in place. See
[`ENHANCEMENTS.md`](ENHANCEMENTS.md) for what this edition adds and
[`CHANGELOG.md`](CHANGELOG.md) for its version history (v1.0.0 upstream
baseline, v1.1.0 enhancements). All original work belongs to Matt Pocock and
the upstream contributors; licence MIT (see `LICENSE`).
