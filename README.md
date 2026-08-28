# Soumadeb Pain — Academic Website

A static academic website designed for GitHub Pages. It uses only HTML, CSS and a small amount of JavaScript, so there is no build step and no software framework to maintain.

## Files
- `index.html` — About + News
- `research.html` — Research and publications
- `teaching.html` — Teaching-assistant experience
- Each HTML page includes its own styling. The homepage JavaScript for the typewriter effect is also included directly in `index.html`.
- `assets/profile.jpg` — profile photograph
- `Soumadeb_Pain_CV.pdf` — downloadable CV

## Put it online with GitHub Pages
1. Sign in to GitHub.
2. Create a **public** repository named exactly `SoumadebP.github.io`.
3. Upload every file and folder from this website package to the repository root.
4. Open the repository's **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select branch **main** and folder **/(root)**, then save.
7. After GitHub finishes deploying, visit `https://soumadebp.github.io/`.

## Updating later
Edit the relevant HTML file directly on GitHub, or replace `Soumadeb_Pain_CV.pdf` with an updated PDF using the same filename. Replacing `assets/profile.jpg` updates the portrait without changing the HTML.


## Previewing locally

For the full multi-page site, keep `index.html`, `research.html`, `teaching.html`, and `Soumadeb_Pain_CV.pdf` in the same folder. Open `index.html` from that folder. The Research and Teaching links are relative links and will work on GitHub Pages when all files are uploaded together at the repository root.
