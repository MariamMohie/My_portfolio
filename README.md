# Mariam Mohie | Portfolio

A static portfolio site (plain HTML, CSS and JavaScript, no build step).

## Structure
- `index.html`: the whole page (styles and scripts are inside it)
- `assets/img/`: profile photo, freelance cover, app screens (`app/`) and certificate images (`certs/`)
- `assets/cv/`: the two downloadable CV PDFs

## Host on Netlify
1. Go to https://app.netlify.com/drop (or Sites > Add new site > Deploy manually).
2. Drag this whole folder (the one containing `index.html`) onto the page.
3. Netlify gives you a link. Rename it under Site configuration > Change site name.

Or connect a Git repository: leave the build command empty and set the publish directory to `/`.

## Editing
- Text and sections: edit `index.html`.
- Colors: change the variables at the top of the `<style>` block (`--accent`, `--accent2`, ...).
- To replace a CV, overwrite the PDF in `assets/cv/` and keep the same file name.
