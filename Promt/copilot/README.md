Copilot prompts directory

All Copilot prompts live here and are executed from this folder.

Usage

- Place any Copilot prompt file (*.md) in this folder.
- To run a review prompt, call the assistant and specify which homework to review, e.g.:
  "перевірити hw-06"

Conventions

- `HomeWork/Promt/copilot/frontend-review.md` — canonical Frontend Mentor / Code Reviewer prompt.
- Each homework folder should contain two files after a review:
  - `notes.md` — short checklist summary (from `REVIEW_TEMPLATE.md`).
  - `frontend-review-notes.md` — detailed review following `HomeWork/Promt/copilot/frontend-review.md`.

Migration note

I've moved the canonical `frontend-review.md` into this folder and updated references in the workspace. Going forward, all Copilot prompt files will be stored here and executed from this directory.
