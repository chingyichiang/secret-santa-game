# Secret Santa Game 🎅

A browser-based Secret Santa assignment app. Enter your group's names, hit the button, and everyone gets randomly assigned a recipient — no duplicates, no one assigned to themselves.

**[▶ Try it live](https://chingyichiang.github.io/secret-santa-game/)**

---

## What it does

- Takes a list of participant names and emails
- Randomly assigns each person a unique Secret Santa recipient
- Generates a private verification code for each participant so they can check their assignment discreetly
- Runs entirely in the browser — no backend, no install, no data stored

## How to use

1. Open the [live app](https://chingyichiang.github.io/secret-santa-game/)
2. Click **Create New Game** and fill in the game details
3. Add all participants (minimum 3)
4. Click **Generate Secret Santa Assignments**
5. **Before closing the tab** — screenshot or note down each participant's code from the results page
6. Share each person's code with them privately
7. Participants enter their code under **Check My Assignment** to see who they're buying for

> ⚠️ **Important:** Assignments are stored in browser memory only. If the organizer refreshes or closes the tab, the codes will no longer work. Make sure to save and share all codes before leaving the page.

Or run it locally:

```bash
git clone https://github.com/chingyichiang/secret-santa-game.git
cd secret-santa-game
open index.html
```

## Known limitations

- **No persistent storage** — assignments exist only for the duration of the browser session. The organizer must share all codes before closing the tab.
- Participants need to check their assignment on the same browser session, or the organizer needs to stay on the page while participants look up their codes.

## Potential improvements

- [ ] Save assignments to `localStorage` so they persist across refreshes
- [ ] Add a backend (e.g. Firebase) so codes work across devices and sessions

## Built with

- HTML / CSS / JavaScript

## Background

Built as a hands-on experiment in shipping something simple end-to-end — from idea to a working, shareable app. Inspired by a manual Secret Santa process I wanted to make easier.
