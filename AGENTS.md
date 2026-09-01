# AGENTS.md

## Project

This repository contains the production system and canonical documentation for
the children's educational animation project **Mela i Piko**.

Before making any meaningful project decision, read:

- `PROJECT_CONTEXT.md`
- relevant files under `docs/`
- relevant character or world bible files

The repository is the canonical source of truth.
Do not rely on assumptions from previous conversations if they conflict with repository files.

## Working principles

Follow this order of priorities:

1. educational quality,
2. safety and suitability for children,
3. character and visual consistency,
4. maintainability,
5. reproducibility,
6. automation,
7. production speed.

Do not optimize for mass production at the expense of quality.

## Current project phase

The project is currently in the **pre-production / visual development phase**.

Do NOT build the full automated production pipeline yet.

Current priorities:

1. Product Bible
2. Mela Character Bible
3. Mela canonical visual design
4. Piko Character Bible
5. Piko canonical visual design
6. World / Style Bible
7. pilot episodes
8. only then automation

## Change policy

Before making a significant architectural or creative change:

1. inspect existing canonical documents,
2. identify conflicts or open questions,
3. explain the proposed change,
4. prefer updating an existing source-of-truth file rather than duplicating information.

Do not silently redefine locked character traits, colors, educational rules, or episode structure.

## Status terminology

Use these states:

- `DRAFT` — still being designed
- `CANDIDATE` — proposed version under testing
- `LOCKED` — canonical and should not change without an explicit decision
- `DEPRECATED` — kept only for history

Do not treat a DRAFT value as a hard constraint unless clearly marked as such.

## Documentation style

Documentation should be:

- explicit,
- structured,
- implementation-friendly,
- versionable,
- free of unnecessary marketing language.

Use Markdown for human-readable bibles.

Use JSON / JSON Schema only when the structure has stabilized enough to be consumed programmatically.

## Source-of-truth policy

Avoid maintaining the same project decision in multiple canonical documents.

When existing content is moved into the canonical repository structure:
- prefer moving or refactoring the existing document over creating a duplicate,
- preserve useful existing content,
- update references to the new canonical path,
- remove obsolete duplicate files after migration.

Canonical paths should use stable names without version suffixes.

Prefer:

`docs/product-bible.md`

over:

`docs/product-bible-v1.md`

Document history belongs in Git.
Document status and semantic version may be stored inside the document.

## Git

Prefer small, coherent commits.

Do not mix:

- character design decisions,
- infrastructure changes,
- episode content,
- unrelated refactoring

in a single commit.

Commit messages should describe the project-level intent.

Examples:

- `docs: add Mela character bible draft`
- `docs: lock Mela color palette`
- `episode: add EP001 shadow storyboard`
- `production: add episode schema validator`

## Creative lock policy

Do not silently convert exploratory creative choices into locked specifications.

For visual design distinguish between:

- LOCKED — explicitly approved and canonical,
- CANDIDATE — preferred direction under evaluation,
- DRAFT — working assumption,
- OPEN — not yet decided.

For character appearance, canonical visual references have higher authority
than textual prompts once those references are approved.

## Human approval

Human approval is mandatory for:

- final character design,
- educational claims,
- final storyboard,
- questionable AI generations,
- publishing.

Automation should support human review, not eliminate it.