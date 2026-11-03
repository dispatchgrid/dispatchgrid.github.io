# dispatchgrid.github.io

Root user site for **Mawanella OPD duty roster**.

This repository mirrors the app in [dispatchgrid/opd-roster](https://github.com/dispatchgrid/opd-roster)
so the roster is reachable from the domain root (`https://dispatchgrid.github.io/`). Publishing at the
root keeps home-screen shortcuts working even when a browser installs the origin instead of the full path.

Files:

- `index.html` — app shell
- `styles.css` — design tokens, grid, light/dark themes
- `app.js` — data layer, views, inline editing, caching
- `sw.js` — offline app shell
