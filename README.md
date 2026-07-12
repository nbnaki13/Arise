# Arise

A personal habit system. Every number is real: automaticity follows the Lally et al. habit-formation curve, milestones are true accumulated quantities, and the daily Vitality Score is computed from what you actually logged. No XP anywhere.

## Deploy free on GitHub Pages (no terminal needed)

1. Go to github.com, create a new repository (e.g. `arise`), set it to Public.
2. On the empty repo page, click "uploading an existing file" and drag ALL files in this folder in (index.html, sw.js, manifest.webmanifest, the three PNG icons, this README). Commit.
3. Repo Settings -> Pages -> Source: "Deploy from a branch" -> Branch: main, folder: / (root). Save.
4. Wait about a minute. Your app is live at `https://YOURNAME.github.io/arise/`

Updating later: edit or re-upload index.html in the GitHub web UI and commit. The app picks up the new version on next launch.

## Install on iPhone

1. Open the URL in Safari.
2. Share button -> Add to Home Screen.
3. Open it from the icon. It runs full screen and works offline after the first load.

Also open the same URL on your Mac; note that data does not sync between devices yet (phase 2). Log on the phone.

## Reminders (one-time setup, native iOS, free)

Shortcuts app -> Automation -> + -> Time of Day -> Daily, and turn "Run Immediately" OFF so it notifies. Action: "Show Notification". Optionally add "Open URL" with your app URL.

- 06:00  Wake up. Check in.
- 08:00  Vitamins + protein.
- 12:30  Water check: 1.5 L by now.
- 18:30  Training window open.
- 21:00  Reading + wind down.
- 21:45  Phone down. Bed by 22:00.

(The same list lives in the app under Settings.)

## Data safety

All data lives in this browser's localStorage until sync ships in phase 2. Export a JSON backup weekly from Settings. Clearing Safari website data erases the app's data.

## Roadmap

- Phase 2: Supabase free-tier sync (phone + Mac), Fitbit Web API for automatic steps and sleep verification.
- Phase 3: weekly Gate Report, smarter reminders, more quests.
