
# CoachBot Admin (prototype)

Static prototype with interlinked admin pages:

- `index.html` — Clients
- `admin-planner.html` — Planner (build plan)
- `admin-report-unified.html` — Report
- `admin-exercises.html` — Exercises library
- `admin-settings.html` — Settings

## Run locally
Open `index.html` in a browser or start a simple HTTP server:

```sh
python3 -m http.server -d . 8080
```

## Deploy to GitHub Pages
1. Create a new repo and push the contents of this folder.
2. In GitHub, open **Settings → Pages**, set **Branch:** `main` (or `master`) and **Folder:** `/root`.
3. Your site will be available at `https://<user>.github.io/<repo>/`.
