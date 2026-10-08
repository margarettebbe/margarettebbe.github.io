# Margaret Tebbe portfolio

A website designed for GitHub Pages. It uses plain HTML and CSS, so there is no build step and very little to break.

## Start here

1. Open all five `.html` files in a text editor.
2. Search for text inside `[square brackets]` and replace each placeholder. Also replace drafting prompts such as “Another title” and “Description.”
3. Preview the site by double-clicking `index.html`.
4. Commit everything in this folder to the root of the `margarettebbe.github.io` repository.

## Pages

- `index.html` — homepage and featured work
- `about.html` — biography, portrait, and quick facts
- `research.html` — three research project features
- `teaching.html` — teaching statement and selected courses
- `cv.html` — web/print CV
- `assets/styles.css` — all colors, typography, layout, and responsive rules

## Replace an image placeholder

Put compressed JPG or WebP images in `assets/images/`. Aim for 1600–2400 pixels on the long edge and generally under 1 MB.

Find an image placeholder such as:

```html
<div class="image-slot" role="img" aria-label="Placeholder for a portrait">
  <span class="slot-label">Portrait</span>
</div>
```

Replace it with:

```html
<img class="site-image" src="assets/images/portrait.jpg" alt="A short, useful description of the photograph">
```

The included `.site-image` style gives replacement images a consistent editorial crop. Use meaningful alternative text. If an image is purely decorative, use `alt=""`.

## Add a PDF CV

Put the current PDF at `assets/docs/margaret-tebbe-cv.pdf`. The CV page already links to that filename, so future updates only require replacing the PDF with a new file that has the same name.

## Change colors or fonts

The first lines of `assets/styles.css` contain the palette and font choices. Change `--ink`, `--paper`, `--accent`, and `--moss` to update the whole site.

The site loads Cormorant Garamond and Inter from Google Fonts, then falls back to common system fonts. To use different Google Fonts, update the font link in each HTML file and the `--serif` / `--sans` values in the stylesheet.

## Publish with GitHub Pages

1. Upload or push all files and folders to the `main` branch of the `margarettebbe.github.io` repository. Keep `index.html` at the repository root.
2. On GitHub, open **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select branch **main**, folder **/(root)**, then **Save**.
5. GitHub will publish the site at `https://margarettebbe.github.io/`. The first publication can take a few minutes.

Because the repository is named `margarettebbe.github.io`, all links use simple relative paths and no base URL needs to be configured.

## Before publishing

- Replace every item in `[square brackets]`.
- Confirm that the email address and institutional affiliation are current.
- Add descriptive text for every real image.
- Check the site on a phone and a computer.
- Remove any sample CV entries that are not needed.

## Optional custom domain

Add the domain in **Settings → Pages → Custom domain**, then follow GitHub's displayed DNS instructions. Do not add a `CNAME` file unless you are ready to connect the domain.
