# Suramya Angdembay Portfolio

Static GitHub Pages site. `index.html` is a short home page (bio, news, papers); `research.html` carries the longer about text, research entries, projects, talks, honors, and experience. Both share `styles.css` and `script.js`.

## Local preview

Open `index.html` directly in a browser, or run:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## GitHub Pages deploy

1. Create a repository named `SuramyaAngdembay.github.io`.
2. Push these files to the repository's default branch.
3. In GitHub, open Settings > Pages and publish from the root of the default branch.

The CV button points to `assets/suramya-angdembay-cv.pdf` (built from `career-suramya/cv/cv.tex`; copy the new `cv.pdf` here whenever the CV changes). The older `assets/suramya-angdembay-resume.pdf` is kept for existing links.
