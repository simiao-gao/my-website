# Simiao Gao, Ph.D. — Academic Profile Website

This repo contains a static academic profile website built with HTML/CSS, generated from the CV content.

## Project structure

- `index.html` — main profile page content
- `styles.css` — responsive styling
- `CV.pdf` — optional (your downloadable resume)
- `photo.jpg` — optional profile image

## Local test

```bash
cd ~/Sites/my-website
python3 -m http.server 8001
open http://localhost:8001
```

## GitHub deployment

```bash
cd ~/Sites/my-website
git status
git add .
git commit -m "Academic profile: Simiao Gao, Ph.D."
# replace with your GitHub username
git remote add origin https://github.com/YOUR_USERNAME/my-website.git
git push -u origin main
```

Then open the repo on GitHub and set:
Settings → Pages → Source: `main` / `root`.

Live site: `https://YOUR_USERNAME.github.io/my-website/`

## Optional enhancements

- Add analytics (Plausible or GA4) in `index.html`
- Add a simple contact form (Formspree)
- Add structured data (`<script type="application/ld+json">` for SEO)
- Add extra pages (`publications.html`, `teaching.html`) and link them

## Update flow

1) Edit `index.html` / `styles.css`
2) `git add .`
3) `git commit -m "Update profile"`
4) `git push`

## Notes

- Make sure to include your personal `CV.pdf` and `photo.jpg` before pushing.
- If you use a custom domain, add a `CNAME` file and configure DNS accordingly.
