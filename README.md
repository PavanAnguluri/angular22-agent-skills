# angular22-agent-skills

![skills.sh Version](https://img.shields.io/badge/skills.sh-v1.0-blue)
![Angular Target](https://img.shields.io/badge/Angular-v22-red)
![Angular](https://img.shields.io/badge/Angular-Framework-DD0031?logo=angular&logoColor=white)
![Built with Angular 22](https://img.shields.io/badge/Built%20with-Angular%2022-DD0031?logo=angular&logoColor=white)

Production-ready Angular 22 skill pack for `skills.sh` and agent-driven development workflows.

This repository gives coding agents a high-signal execution context for modern Angular architecture, including signals, native control flow, deferrable views, typed forms, Vitest, and zoneless runtime patterns.

## Why This Repository

- Enforces Angular 22-first decisions.
- Reduces legacy drift in AI-generated code.
- Gives repeatable, editor-agnostic setup paths.
- Ships as a clean, publishable GitHub repository.

## Quick Start

```bash
npx skills add PavanAnguluri/angular22-agent-skills
```

If you fork this repository, replace `PavanAnguluri/angular22-agent-skills` with your namespace.

## Actionable Setup Guide

The following execution paths are designed to be copy-paste friendly across common AI coding environments.

### Cursor

1. Open your target Angular workspace in Cursor.
2. Open Cursor terminal in the project root.
3. Run:

```bash
npx skills add PavanAnguluri/angular22-agent-skills
```

4. Start your prompt with an instruction such as:
	Use the installed Angular 22 skills and follow signals, control-flow blocks, Vitest, and zoneless guidance.

### Windsurf

1. Open the workspace in Windsurf.
2. Use the integrated terminal at repository root.
3. Run:

```bash
npx skills add PavanAnguluri/angular22-agent-skills
```

4. In your first agent message, explicitly tell it to apply this skills bundle.

### Claude Code

1. Open terminal in your project root.
2. Install the skill repository:

```bash
npx skills add PavanAnguluri/angular22-agent-skills
```

3. When prompting Claude Code, include:
	Follow the angular22-agent-skills repository standards for architecture, templates, testing, and runtime behavior.

### GitHub Copilot

1. Open the project in VS Code with Copilot enabled.
2. In terminal, run:

```bash
npx skills add PavanAnguluri/angular22-agent-skills
```

3. In Copilot Chat, begin with:
	Use the installed Angular 22 skills pack and enforce modern non-legacy patterns.

## Skill Catalog

The manifest is defined in [skills.sh.json](skills.sh.json), referencing:

- [ng22-architecture-composition](skills/ng22-architecture-composition/SKILL.md)
- [ng22-reactivity](skills/ng22-reactivity/SKILL.md)
- [ng22-control-flow](skills/ng22-control-flow/SKILL.md)
- [ng22-deferrable-views](skills/ng22-deferrable-views/SKILL.md)
- [ng22-routing-lazy](skills/ng22-routing-lazy/SKILL.md)
- [ng22-testing](skills/ng22-testing/SKILL.md)
- [ng22-forms](skills/ng22-forms/SKILL.md)
- [ng22-vitest](skills/ng22-vitest/SKILL.md)
- [ng22-zoneless](skills/ng22-zoneless/SKILL.md)

## Coverage Highlights

- Signal-centric state and derived computation.
- Native template control flow using `@if`, `@for`, `@switch`, and `@defer`.
- Feature-oriented standalone architecture.
- Lazy routing and route guard discipline.
- Typed reactive forms and explicit validation.
- Vitest-oriented Angular testing strategies.
- Zoneless-compatible UI update and async patterns.

## Local Authoring Workflow

When adding a new skill:

1. Create `skills/<skill-name>/SKILL.md`.
2. Add its path to [skills.sh.json](skills.sh.json).
3. Update this README catalog section.
4. Validate front matter and path resolution.

## Publish and Branch Workflow

This repository is designed to be maintained via `develop` and promoted to `main` by pull request.

```bash
git checkout develop
git pull origin develop
git add .
git commit -m "Update skills content"
git push origin develop
```

Then open a PR from `develop` to `main` with a summary of changed skills and verification notes.

## Project Standard

Keep every skill concrete, up-to-date, and executable by agents with minimal ambiguity.
