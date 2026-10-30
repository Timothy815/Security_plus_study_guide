# Security+ Quest

Interactive, adaptive study app for the CompTIA Security+ (SY0-701) exam.

`index.html` is fully self-contained: questions, fonts, styles and scripts are all inlined. No build step.

## Publish on GitHub Pages

1. Create a new repository on GitHub (for example `security-plus-quest`). Public repos get Pages for free.
2. Upload `index.html` and this `README.md` to the repository root (Add file → Upload files → Commit).
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, set Source to **Deploy from a branch**, Branch to **main**, folder **/ (root)**, then **Save**.
5. After a minute or two the site is live at `https://<your-username>.github.io/security-plus-quest/`.

## Notes for students

- Progress (history, XP, streaks, leaderboard) is saved in your browser's local storage on that device. Clearing browser data or switching devices or browsers starts fresh.
- Works offline once loaded.

## Updating

Replace `index.html` with a newer export and commit. Student progress is kept because it is stored in the browser, not in the file.
