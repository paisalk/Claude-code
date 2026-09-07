# Practice prompts for Cursor iOS

Copy one prompt at a time into the iOS app. Pick this repository and the `main` branch (or the branch your agent created). After each run, review the pull request on your phone, then merge or send a follow-up.

## 1. Watch an agent finish a tiny change

```
On playground.html, change the title to "My Cursor Playground" and the accent color to a warm orange. Keep the rest of the layout.
```

Then lock the phone. You should see a Live Activity / notification when the turn finishes.

## 2. Follow up in the same thread

```
Make the Tap me button also reset to 0 if I long-press it, and show a short hint under the button.
```

## 3. Design Mode (screenshot)

1. Open `playground.html` on your phone (GitHub file preview, or a local/GitHub Pages URL).
2. Screenshot it.
3. In the iOS app, attach the screenshot, circle tile 1, and send:

```
The circled area feels too plain. Give each practice tile a distinct icon and a slightly stronger border. Match the existing dark theme.
```

## 4. Voice

Dictate something like:

```
Add a short greeting at the top of playground.html that says hello and the current local time. Keep it mobile friendly.
```

## 5. Review a real app change

The Bitcoin page lives at `index.html`. Try:

```
On the Bitcoin exchange page, add EUR as a third currency next to USD and THB. Reuse the existing rate-fetching pattern and keep the converters working.
```

Only send this after you are comfortable with the playground. It touches live rates and more JavaScript.

## 6. Investigate, don't code

```
Read this repo and explain in a short comment on the PR what playground.html and index.html each do, and which file I should edit first from iOS.
```

## Tips

- One request per turn is easier to review on a phone.
- If the repo picker is empty, connect GitHub at [cursor.com](https://cursor.com), then pull down on the iOS inbox to refresh.
- You cannot create the GitHub connection, secrets, or environments from the iOS app. Those stay on the web.
- Agents started on iOS show up at [cursor.com/agents](https://cursor.com/agents) and in the desktop Agents Window.
