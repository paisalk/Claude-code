# Claude-code

A first repo for learning **Cursor on iOS**.

The iOS app is not a code editor. You pick this repository, send a task, watch a Cloud Agent work, then review and merge the pull request from your phone.

## What’s in here

| File | What it’s for |
|---|---|
| [playground.html](playground.html) | Safe canvas for your first iOS tasks |
| [index.html](index.html) | Existing Bitcoin / satoshi rate page (USD + THB) |
| [PRACTICE.md](PRACTICE.md) | Copy-paste prompts for the iOS app |
| [AGENTS.md](AGENTS.md) | Notes for agents that run against this repo |

## Use it from Cursor for iOS

1. Install [Cursor](https://apps.apple.com/app/cursor/id6767085653) (iOS 26+ / iPadOS 26+).
2. Sign in with a paid Cursor plan (Pro and up). Free accounts can open the app but cannot start agents.
3. Confirm this GitHub repo appears in the picker. If it doesn’t: connect GitHub at [cursor.com](https://cursor.com), then pull down on the inbox to refresh.
4. Choose this repo and `main`.
5. Paste a prompt from [PRACTICE.md](PRACTICE.md).
6. Leave the app. Live Activities and push notifications tell you when the agent needs you.
7. Open the PR, read the diff, merge or send a follow-up.

## Open the pages

These are static files. On a computer:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000/playground.html`.

On your phone, open the files on GitHub or enable GitHub Pages on this repo so you can screenshot them for Design Mode.

## What the iOS app cannot do

Connect GitHub, create repos, add secrets, set up Cloud Agent environments, or manage billing (except App Store subscriptions). Do those on the web, then come back to the phone.
