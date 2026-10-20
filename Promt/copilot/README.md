Copilot prompts directory

All Copilot prompts live here and are executed from this folder.

Usage

- Place any Copilot prompt file (*.md) in this folder.
- To run a review prompt, call the assistant and specify which homework to review, e.g.:
  "перевірити hw-06"

Conventions

- `HomeWork/Promt/copilot/frontend-review.md` — canonical Frontend Mentor / Code Reviewer prompt.
- Each `HomeWork/hw-*` folder stores review materials under `Überprüfung/`:
  - `Überprüfung/REVIEW_TEMPLATE.md` — review criteria and homework-specific requirements.
  - `Überprüfung/copilot/NOTES.md` — short checklist result from the Copilot review.
  - `Überprüfung/copilot/frontend-review-notes.md` — detailed Copilot analysis.
  - `Überprüfung/codex/visual-review-notes.md` — visual review result from the Codex prompt.

Migration note

All Copilot prompts live here. Codex prompts and visual review instructions live in `HomeWork/Promt/codex/`.
