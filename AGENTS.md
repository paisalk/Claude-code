# Agent notes

This repository is a **Cursor iOS learning playground**, not a production app.

## What exists

- `playground.html` — static practice canvas for first mobile-agent tasks (visual edits, tiny JS).
- `index.html` — Bitcoin / satoshi exchange-rate page (USD + THB, Binance public APIs).
- `PRACTICE.md` — copy-paste prompts the owner can send from Cursor for iOS.
- `README.md` — how to use this repo from the iOS app.

## How to work here

- Prefer **small, reviewable diffs**. The owner is learning to review PRs on a phone.
- Default to editing `playground.html` unless the task names the Bitcoin page.
- Do not add a build step, bundler, or backend unless asked. Keep it static HTML/CSS/JS.
- Do not remove working Bitcoin converter behavior unless the task is explicitly about that page.
- After UI changes, sanity-check that the page still works on a narrow phone viewport.
