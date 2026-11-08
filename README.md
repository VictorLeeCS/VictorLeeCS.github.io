# Personal portfolio (static GitHub Pages site)

This is a static version of the original FastAPI portfolio. No Python, server, or build step is needed.

## Preview locally
Open `index.html` in a browser.

## Publish on GitHub Pages
1. Create a public GitHub repository named `YOUR-USERNAME.github.io` (replace `YOUR-USERNAME` with your GitHub username).
2. Upload the **contents** of this folder to the repository root, including `index.html`, `css/`, `js/`, and `assets/`.
3. In repository **Settings > Pages**, select **Deploy from a branch**, branch **main**, folder **/(root)**, then Save.
4. Your website will be at `https://YOUR-USERNAME.github.io/` after publishing.

## Edit your site
- `index.html`: name, bio, education, work experience, projects, skills, email, links.
- `css/style.css`: colors and layout.
- `js/script.js`: current-year footer behavior.
- `assets/resume.pdf`: replace with your updated resume (be aware that this PDF will be public).

No FastAPI, Jinja2, Uvicorn, or requirements.txt are needed.
