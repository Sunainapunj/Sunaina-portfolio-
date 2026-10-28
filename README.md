# Sunaina — Portfolio
Static site, no build step, no dependencies.
- `index.html` landing page (6 folders, sound toggle)
- `case-studies/` three original case-study files (unmodified, self-contained) plus `qik-card-game.html`
- `project-pages/` RA.A.M and AI Companion work-in-progress pages
- `assets/` cover images extracted from the case studies, plus `wip.css`
## Run locally
Open `index.html` in a browser, or run `python3 -m http.server` in this folder and visit http://localhost:8000.
## Deploy
Upload the whole folder to any static host (Netlify Drop, GitHub Pages, Vercel, Cloudflare Pages). All paths are relative.
## Notes
Sound uses the Web Audio API, starts only after a click/keypress, is off by default, and the choice is stored in localStorage.

## Resume
Place your resume PDF at `assets/Sunaina_Resume.pdf` (or change `resumePath` in `index.html`). The download button is wired to that path.
