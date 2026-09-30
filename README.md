# Academic website — Agustina Martínez

Static site (HTML/CSS/JS, no build step), designed for GitHub Pages.

## Structure

```
index.html            single-page site (Home, Research, Teaching, CV, Contact)
styles.css            styles
script.js             smooth scrolling, active-section highlighting, mobile menu
assets/img/           profile.jpg  (square photo, ≥ 400×400 px)
assets/files/         CV.pdf, JMP.pdf, other papers
.nojekyll             tells GitHub Pages to serve files as-is
```

## Publishing on GitHub Pages

1. Create a public repository named `<username>.github.io`.
2. Upload the contents of this folder (not the folder itself) to the repository root.
3. Settings → Pages → Source: *Deploy from a branch*, branch `main`, folder `/ (root)`.
4. The site will be available at `https://<username>.github.io` within a few minutes.

## Items to complete

Search `index.html` for `Replace` and `<!--` to find placeholders: email, profile links,
teaching modules, paper PDFs (uncomment the link lines once the files are in `assets/files/`),
and the IEB report block.
