# angular22-agent-skills

Angular 22 skill pack for `skills.sh`. This repository packages practical guidance for modern Angular architecture, templates, performance, testing, and runtime behavior in a publishable GitHub repo.

## Repository Purpose

Use this repository as a reusable skill bundle for local agents and tools that understand the `skills.sh` manifest format. The content is intentionally opinionated so an agent can follow current Angular 22 patterns without drifting into legacy approaches.

## Install

Add the repository to a local `skills.sh` environment with:

```bash
npx skills add PavanAnguluri/angular22-agent-skills
```

If you fork or mirror the repo, replace the namespace with your own GitHub account or organization.

## What Is Included

The root manifest is [skills.sh.json](skills.sh.json), and it references these skill files:

- [ng22-architecture-composition](skills/ng22-architecture-composition/SKILL.md)
- [ng22-reactivity](skills/ng22-reactivity/SKILL.md)
- [ng22-control-flow](skills/ng22-control-flow/SKILL.md)
- [ng22-deferrable-views](skills/ng22-deferrable-views/SKILL.md)
- [ng22-routing-lazy](skills/ng22-routing-lazy/SKILL.md)
- [ng22-testing](skills/ng22-testing/SKILL.md)
- [ng22-forms](skills/ng22-forms/SKILL.md)
- [ng22-vitest](skills/ng22-vitest/SKILL.md)
- [ng22-zoneless](skills/ng22-zoneless/SKILL.md)

Each skill file contains front matter plus a focused guide that covers one Angular 22 best-practice area.

## Coverage

- Signals, computed values, signal inputs, and model binding.
- Native block syntax for `@if`, `@for`, `@switch`, and `@defer`.
- Feature-oriented architecture with standalone composition.
- Route-level lazy loading and guard discipline.
- Typed forms and explicit validation flow.
- Vitest-based testing guidance for Angular projects.
- Zoneless-friendly state updates, async boundaries, and SSR considerations.

## Local Development

If you want to edit or extend the repo locally, work from the repository root and keep the manifest and skill paths aligned:

```bash
git status
```

When adding a new skill:

1. Create a new `skills/<skill-name>/SKILL.md` file.
2. Add the new path to `skills.sh.json`.
3. Update this README so the new skill appears in the repository catalog.
4. Validate that the manifest path resolves and that the skill has YAML front matter.

## Publishing Workflow

This repository is already initialized as a GitHub project and tracks the `develop` branch. If you need to recreate the publishing flow in a new environment, the basic sequence is:

```bash
git init
git checkout -b develop
git add .
git commit -m "Initial angular22-agent-skills"
git remote add origin https://github.com/PavanAnguluri/angular22-agent-skills.git
git push -u origin develop
```

## Maintenance Notes

- Keep examples modern and avoid legacy Angular patterns.
- Keep each skill self-contained and easy to scan.
- Prefer small, concrete examples over generic prose.
- Update the manifest whenever a skill file changes location or name.

## Repository Goal

Make the catalog broad enough to cover architecture, templates, performance, forms, testing, and runtime behavior while staying concise enough for agents to use directly.
