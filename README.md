# Training-app

Progressive web app for logging training sessions. Served via GitHub Pages at
<https://jesse-vdr.github.io/Training-app/>.

Writes events to the private [Jesse-vdR/Jesse](https://github.com/Jesse-vdR/Jesse)
repo (`training/log/events.jsonl`) using a fine-grained personal access token
that the user enters on first launch. The token lives only in the phone's
localStorage; this public repo holds no secrets.

## Layout (planned)

- `index.html` — app shell
- `app.js` — UI + GitHub API sync
- `manifest.json` — PWA manifest (install to home screen)
- `sw.js` — service worker (offline shell cache)
- `icon-192.png`, `icon-512.png` — app icons

## Pages setup

Settings → Pages → Source: *Deploy from a branch* → `main` / `/` (root).
