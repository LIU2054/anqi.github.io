# Anqi Liu — Academic Homepage

Static academic homepage for Anqi Liu, Postdoctoral Researcher in the Hydro-climatology Research Lab at POSTECH. The site is one self-contained `index.html` file (no build step).

## GitHub Pages

A `.nojekyll` file is included so Pages serves the files directly.

1. Open **Settings → Pages**.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select branch **`main`** and folder **`/ (root)`**, then save.

The site will be published at:

https://liu2054.github.io/anqi.github.io/

## Profile photo

`index.html` loads `profile.jpg` from this folder. Until that file is added, the page shows an **AL** monogram. Place `profile.jpg` next to `index.html` to use a portrait.

## Hidden profile links

Website and LinkedIn were placeholders (`href="#"`) and are commented out so they are not dead links. In `index.html`, search for `To re-enable`, replace `#` with the real URL, and move the anchor into the profile links.

Honors & Awards and Technical Skills stay in HTML comments, as on the previous page, and are not shown.
