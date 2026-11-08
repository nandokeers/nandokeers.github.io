# Portfolio site

Plain HTML + CSS. No build step: open `index.html` in a browser to see it.

## Edit
- All your content is in `index.html`. Look for `<!-- EDIT -->` comments.
- Put your CV in `assets/cv.pdf` and (optional) a photo in `assets/photo.jpg`.
- Change the accent color with `--accent` at the top of `style.css`.

## Publish for free (GitHub Pages)
1. Create a GitHub repo named `nandokeers.github.io`.
2. Upload `index.html`, `style.css` and the `assets` folder.
3. Settings → Pages → Source: "Deploy from a branch" → `main` / root.
4. After ~1 minute the site is live at `https://nandokeers.github.io`.

Netlify or Cloudflare Pages work too (drag and drop the folder).

## CV
The PDFs in `assets/` (`cv-en.pdf`, `cv-nl.pdf`) are generated from `cv-source/cv.html`.
Open that file in Chrome, switch `lang="en"` / `lang="nl"` on the `<html>` tag, and use Print → Save as PDF
(paper A4, margins none, background graphics on).
