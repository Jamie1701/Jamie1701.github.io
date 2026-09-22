# Jamie1701.github.io

Personal portfolio site, published at [jamie1701.github.io](https://jamie1701.github.io).

Plain HTML/CSS, no build step — GitHub Pages serves this repo's `main` branch directly.

## Structure

- `index.html` — all page content (About, Projects, CV, Contact)
- `css/style.css` — all styling
- `assets/cv/CV.pdf` — your CV, add this file yourself (see `assets/cv/README.md`)

## Editing content

Open `index.html` in any text editor. Each section is clearly marked with an
HTML comment. To add a project, copy an existing `<article class="project-card">`
block inside `#projects` and edit the title, tags, description, and link.

## Preview locally before pushing

From this folder, run:

```
python3 -m http.server 8000
```

then open http://localhost:8000 in a browser. Refresh after each save.

## Publishing

```
git add -A
git commit -m "Update site"
git push
```

Changes go live at jamie1701.github.io within a minute or two of pushing to `main`.
