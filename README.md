# Vicky Study Hub — CUET UG 2027

A responsive, single-page study planner built with plain HTML, CSS and JavaScript.

## Features
- Add, edit and delete timetable tasks
- Subjects: Physics, Chemistry, English, GAT, Revision, Break and Other
- Daily completion checkboxes and progress percentage
- Automatic new-day reset when the site is opened on a later date
- Recent history, 7-day chart and current streak
- Export a JSON backup and restore it later
- Mobile-friendly blue-and-white design
- No account, server, paid service or external library required

## Run locally
Open `index.html` in a modern browser.

## Deploy free with GitHub Pages
1. Sign in to GitHub and create a new **public** repository, for example `vicky-study-hub`.
2. Upload `index.html` and `README.md` to the repository's root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/ (root)`, then Save.
6. Wait for GitHub Pages to publish the site. Your URL will look like:
   `https://YOUR-USERNAME.github.io/vicky-study-hub/`

## Data and backup notes
- Study data is stored in the browser's localStorage on the device/browser where the site is used.
- Use **Backup** regularly to download a JSON file.
- Use **Restore** to import a previous backup.
- Clearing browser/site data can erase the local copy.
- This version does not sync data across devices. It intentionally has no login or cloud backend.

## Daily reset behavior
When the app is opened on a new calendar day, today's completion checkboxes start fresh while the task timetable remains. The previous day's completion count is added to History. The app does not run in the background or send reminders.
