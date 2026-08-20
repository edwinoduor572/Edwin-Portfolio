# Edwin Oduor — Portfolio Site

A single-page portfolio built from Edwin's résumé. Plain HTML/CSS/JS — no build step, so it's ready for GitHub Pages as-is.

## Files
- `index.html` — page content
- `style.css` — styling
- `script.js` — footer year + scroll-reveal
- `assets/Edwin_Oduor_Resume.pdf` — downloadable résumé (linked from the "Résumé ↓" button)

## Publish it on GitHub Pages

1. Create a new repository on GitHub (e.g. `edwin-portfolio`).
2. Upload these files to the repo root — either via the GitHub web UI ("Add file → Upload files") or with git:
   ```bash
   git init
   git add .
   git commit -m "Initial portfolio site"
   git branch -M main
   git remote add origin https://github.com/<your-username>/<repo-name>.git
   git push -u origin main
   ```
3. In the repo, go to **Settings → Pages**.
4. Under **Build and deployment → Source**, choose **Deploy from a branch**.
5. Set **Branch** to `main` and folder to `/ (root)`, then **Save**.
6. Wait a minute or two — GitHub will give you a live URL, usually:
   `https://<your-username>.github.io/<repo-name>/`

## Editing later
- Update text directly in `index.html` (job bullets, skills, contact links).
- Colors and fonts are defined as CSS variables at the top of `style.css` under `:root`.
- To swap the résumé PDF, replace `assets/Edwin_Oduor_Resume.pdf` and keep the filename, or update the `href` in `index.html`.
