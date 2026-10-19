# imnotjccc.github.io

Personal academic homepage of Jiayi Chen. Pure HTML/CSS, no build step.

## Files
- `index.html` — all page content (edit text here)
- `assets/style.css` — styles (light/dark theme tokens at the top)
- `assets/Jiayi_Chen_CV.pdf` — CV linked from the "CV" button
- `assets/profile.png` — profile photo (shown as a 2:3 rounded portrait). If missing, the page shows a "JC" monogram.
- `.nojekyll` — tells GitHub Pages to serve files as-is

## Deploy to GitHub Pages
1. On GitHub, create a **public** repository named exactly `imnotjccc.github.io`.
2. Upload everything in this folder (including the hidden `.nojekyll` file) to the `main` branch,
   or from this folder run:
   ```bash
   git init
   git add .
   git commit -m "Initial homepage"
   git branch -M main
   git remote add origin https://github.com/imnotjccc/imnotjccc.github.io.git
   git push -u origin main
   ```
3. Repo → Settings → Pages → Source: "Deploy from a branch", Branch: `main` / `(root)`.
4. After about a minute the site is live at https://imnotjccc.github.io

## Updating
- New publication / news item: copy an existing `<article class="entry">` or `<li>` block in `index.html`.
- Update the CV: replace `assets/Jiayi_Chen_CV.pdf` (keep the filename).
- Update the footer's "Last updated" date.
