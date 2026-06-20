# Shuvam Raghuvanshi — Portfolio

A clean, minimal personal portfolio website (no third-party widgets), ready to host on GitHub Pages.

## Files
- `index.html` — page content
- `style.css` — styling (light/dark theme)
- `main.js` — theme toggle, mobile nav, footer year

## Run locally
Just open `index.html` in a browser, or serve it:

```sh
python3 -m http.server 8000
# then open http://localhost:8000
```

## Deploy on GitHub Pages
1. Create a repo (e.g. `portfolio`) and push these files to the `main` branch.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, set **Source: Deploy from a branch**, **Branch: `main` / `root`**, then **Save**.
4. Your site will be live at `https://Shuvam-Raghuvanshi.github.io/portfolio/`.

To use it as your main profile site at `https://Shuvam-Raghuvanshi.github.io`,
name the repository `Shuvam-Raghuvanshi.github.io` instead.

## Customize
- Update text in `index.html` (about, skills, projects, contact).
- Tweak colors via the CSS variables in `:root` and `[data-theme="dark"]` in `style.css`.
