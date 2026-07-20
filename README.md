# Glenth AI Workflow

> **Context and Discipline — AI-assisted engineering on the Glenth platform**

A single-page presentation on how the Glenth team runs AI-assisted software
engineering: not "how to write code," but *where* and *how* — the source of
truth, the guardrails, and the discipline that keeps an AI agent productive and
safe inside a real codebase. Available in English (default) and Portuguese.

**Live page:** https://carlossantosdev.github.io/glenth-ai-workflow/

## What it covers

- **The real problem** — writing code isn't the hard part; knowing *where* and *how* is.
- **CLAUDE.md** — the single source of truth and orientation index for agents.
- **Skills ecosystem** — orchestration and delegation across specialized skills.
- **The Spec-Driven flow** — seven phases with per-task verification.
- **Technical disciplines** — the rigor the workflow invokes (TDD, debugging, review, verification).
- **Breaking points** — where the human decides and where nothing is compromised.
- **What the process delivers** — and when it's worth it.

## Running locally

The page is fully self-contained — no build step, no dependencies:

```bash
open index.html          # macOS
# or serve it:
python3 -m http.server   # then open http://localhost:8000
```

## Language

Two versions, linked by a switcher in the header:

- **English (default)** — https://carlossantosdev.github.io/glenth-ai-workflow/
- **Português** — https://carlossantosdev.github.io/glenth-ai-workflow/pt-br/

In the underlying Glenth platform, durable documentation and commit messages
follow English (en_US), per market standard.

## License

MIT — see [LICENSE](LICENSE).
