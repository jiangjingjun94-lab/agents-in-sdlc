# Repository instructions

This repository contains Copilot Workshops content and its Astro + Starlight publisher. It is not the Tailspin Toys application repository; do not add application code here.

## Shared project conventions

- Read [`AUTHORING.md`](AUTHORING.md), [`CONTRIBUTING.md`](CONTRIBUTING.md), and [`.github/copilot-instructions.md`](.github/copilot-instructions.md) before making substantial changes.
- For Markdown, follow the applicable files in [`.github/instructions/`](.github/instructions/). Edit lesson source under `docs/`; preserve the manually maintained sidebar and update translations or duplicated prose when relevant.
- Use the [`build-and-verify-docs`](.github/skills/build-and-verify-docs/SKILL.md) skill for the documented verification sequence before committing content changes.
- Keep changes focused and preserve existing repository conventions. Application changes belong in `github-samples/tailspin-toys`.

## Cross-tool handoffs

When handing a task between coding assistants, use [`HANDOFF.md`](HANDOFF.md) to record concise task context, status, decisions, changed files, verification, and next steps. Keep it current and do not put credentials or other secrets in it. The repository is a shared handoff point; it does not directly link accounts or chat sessions.
