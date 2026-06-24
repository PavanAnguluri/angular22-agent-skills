# Contributing to angular22-agent-skills

Thank you for contributing. This repository is designed as a shared Angular 22 guardrail catalog for agent-assisted development.

## Contribution Goals

- Keep skills practical and implementation-ready.
- Prefer modern Angular 22 guidance over legacy approaches.
- Add reusable project-specific guardrails that reduce agent mistakes.

## What to Contribute

- New skill packs for Angular 22 architecture, testing, runtime, and delivery workflows.
- Improvements to existing `SKILL.md` files with clearer rules and examples.
- Better anti-pattern detection and review checklists.
- Documentation improvements in `README.md` and this guide.

## Adding a New Skill

1. Create a new folder at `skills/<skill-name>/`.
2. Add `skills/<skill-name>/SKILL.md` with required front matter:
   - `name`
   - `description`
3. Add the skill path to `skills.sh.json`.
4. Add the skill entry to the README catalog and coverage sections.
5. Verify examples use modern Angular 22 patterns.

## Pull Request Process

1. Branch from `develop`.
2. Keep changes focused and small where possible.
3. Include a clear PR title and summary:
   - What changed
   - Why it changed
   - How it was validated
4. Open PR from `develop` into `main`.

## Style Expectations

- Use concise, direct wording.
- Keep examples executable and realistic.
- Avoid legacy Angular patterns unless specifically documenting migration behavior.
- Prefer signal-first, block-template, and hydration-safe practices.

## Validation Checklist

- Every added skill path in `skills.sh.json` resolves to a real file.
- Every `SKILL.md` contains front matter with `name` and `description`.
- No unintended legacy template syntax (`*ngIf`, `*ngFor`, `*ngSwitch`) appears in modern guidance.
- README remains consistent with the manifest skill list.

## Community Guardrails

Contributors are encouraged to add project-specific rules that reflect real production constraints. The goal is to build a high-signal open-source catalog that helps agents generate better Angular 22 code out of the box.
