# angular22-agent-skills

This repository packages Angular 22 architecture guidance as a `skills.sh`-compatible skill set and is structured to be pushed directly to GitHub.

## Install

Add it to your local `skills.sh` environment with:

```bash
npx skills add <your-username>/<your-repo-name>
```

After publishing to GitHub, replace the placeholder with your real namespace and repository name, for example:

```bash
npx skills add <your-username>/angular22-agent-skills
```

## Publish to GitHub

```bash
git init
git add .
git commit -m "Initial angular22-agent-skills"
git branch -M main
git remote add origin https://github.com/<your-username>/angular22-agent-skills.git
git push -u origin main
```

## Contents

- `skills/ng22-reactivity/SKILL.md`
- `skills/ng22-control-flow/SKILL.md`
- `skills/ng22-deferrable-views/SKILL.md`
- `skills/ng22-architecture-composition/SKILL.md`
- `skills/ng22-routing-lazy/SKILL.md`
- `skills/ng22-testing/SKILL.md`
- `skills/ng22-forms/SKILL.md`
- `skills/ng22-vitest/SKILL.md`
- `skills/ng22-zoneless/SKILL.md`

Each skill file is designed to enforce modern Angular 22 patterns around signals, native block control flow, deferrable views, route-level lazy loading, testing discipline, forms, Vitest, zoneless runtime behavior, and feature-oriented architecture.

## Best-Practice Coverage

- Signals and signal-based inputs for local state and derived state.
- Native control flow blocks for templates.
- Deferrable views for performance-sensitive UI.
- Standalone composition and narrow service boundaries.
- Lazy routing and feature-level composition.
- Behavior-focused testing across components and services.
- Typed reactive forms with explicit validation and submission flows.
- Vitest for fast, deterministic unit and component testing.
- Zoneless-friendly UI updates and explicit async boundaries.

## Design Goals

- Keep the skills practical enough to copy into real Angular 22 work.
- Prefer current Angular guidance over legacy Angular patterns.
- Make the catalog broad enough to cover architecture, templates, performance, forms, testing, and runtime behavior.
- Keep the repository clean, minimal, and ready for publication.
