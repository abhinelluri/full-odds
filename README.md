# Full Odds

A personal full-odds shiny tracker covering hunts, phases, a Gen 3–5 living form dex, carts, collections, a journal and stats.

## Put it on GitHub Pages

1. Create a new repository (for example `full-odds`).
2. Upload every file in this folder to the root of the repo: `index.html`, `sw.js`, `manifest.webmanifest`, and the three icon PNGs.
3. In the repo, open Settings, then Pages. Set Source to "Deploy from a branch", choose `main` and `/ (root)`, and save.
4. After a minute the site is live at `https://<your-username>.github.io/full-odds/`.

## Use it on your phone

Open the site on your phone.

- **iPhone:** in Safari, tap Share, then Add to Home Screen.
- **Android:** in Chrome, choose Install app.

It opens full screen straight into Count mode, keeps the screen awake while you count, and works offline once it has loaded.

## Keep phone and laptop in sync

Data is saved in the browser. To share it between devices:

1. On github.com, go to Settings, then Developer settings, then Personal access tokens, then Tokens (classic).
2. Generate a token with only the **gist** scope.
3. In Full Odds, open Settings, then "Sync between devices", and paste the token.
4. Paste the same token on your other devices. They find the same private gist automatically.

The token never leaves your devices except to talk to GitHub, and it is never included in backups. "Download backup" in Settings gives you a JSON copy of everything at any time.
