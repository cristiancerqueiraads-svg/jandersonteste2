# Landing page — design reference

This is a design mockup created in a visual design tool, exported as a
standalone page. Treat it as a REFERENCE MOCKUP, not production code:
the markup and inline styles carry the design's precise values — colors,
font sizes, spacing, radii, shadows, layout — which an implementation
should replicate faithfully in its own components and styling system
rather than copy wholesale.

## Contents

- `index.html` — entry point for GitHub Pages (a copy of `Main.dc.html`).
- `Main.dc.html` — the artboard (a Design Component: an `<x-dc>`
  template + a small logic class). The values to replicate live in its
  inline `style="…"` attributes and the `<helmet><style>` block.
- `support.js`, `vendor/react*.js` — the runtime that renders the
  component in a browser; not part of the design.
- `.nojekyll` — tells GitHub Pages to serve the files as-is.

## Viewing

Serve the folder (e.g. `python3 -m http.server`) and open `index.html`;
some browsers block the scripts over file://.

## GitHub Pages

1. Go to **Settings → Pages** in the repository.
2. Under **Build and deployment → Source**, choose **Deploy from a branch**.
3. Select branch **main** and folder **/ (root)**, then save.
4. The site will be published at
   `https://cristiancerqueiraads-svg.github.io/jandersonteste2/`.
