# AGENTS.md

Purpose
- Help AI coding agents become productive quickly in this repository.

Quick repository summary
- This workspace contains small static web projects (homework) in `hw-01/` … `hw-07/`.
- There is no build system or test runner; files are plain HTML, CSS, JS.

What an agent should know and do
- Link, don't embed: prefer linking to existing docs (e.g., README, hw/*/README.md).
- Inspect `hw-*/REVIEW_TEMPLATE.md` and `hw-*/NOTES.md` for submission expectations.
- Avoid making broad refactors across student homework without asking the user first.
- For local preview use a simple HTTP server, e.g.: `python -m http.server 8000` from the repo root.

Key files and directories
- [README.md](README.md) — repo overview
- `hw-*/` — each homework lives here; check its `README.md`, `NOTES.md`, and `REVIEW_TEMPLATE.md`.
- [hw-06/REVIEW_TEMPLATE.md](hw-06/REVIEW_TEMPLATE.md) — example review template currently open in the editor.

Conventions and expectations
- Keep edits minimal and focused to the user's request.
- When suggesting fixes, show exact diffs and explain why the change is needed.

If in doubt
- Ask the user before changing multiple files or committing.

Next customizations to consider
- Add per-area instructions (e.g., `AGENTS-frontend.md`) if the repo grows.
