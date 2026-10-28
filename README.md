# Sire Run corporate website

Static GitHub Pages site. No dependencies or build step. `index.html` contains the layout, styles and interactions. The Sire company mark is in `assets/brand/`; official product assets and provenance are in `assets/products/`.

## Publish

Push to the publishing branch and select that branch and `/ (root)` in repository Settings → Pages → Deploy from a branch. `CNAME` specifies `sire.run`; the owner configures DNS. Enable HTTPS once the domain is verified and its certificate is available.

## Content and design

Zati is the flagship: an AI worker workspace in development, evolving from Zatiti. The retired Sire product is not marketed here. The company theme is AI work under human direction; the portfolio covers memory, personal follow-through, learning, agent collaboration, governance checks, verification and decision history. This does not imply the products form an integrated or generally available platform.

The moving mosaic uses only Zati, Serenity and Saka. Nine owner-supplied JPEG illustrations live in `assets/tiles/` (originals remain in `tmp/product-tiles/`). The 15-tile sequence repeats selected artwork: six Zati, four Serenity and five Saka tiles. Every column separates products, including at loop boundaries. JavaScript duplicates each sequence for seamless motion. Captions are HTML, not baked into the images. These are conceptual illustrations, not product screenshots. Saka links point to https://saka.run/. The existing content below the hero and wider project directory are retained.

The original JPEGs are preserved without re-encoding; the nine images total about 20 MB. Image delivery optimization remains a follow-up.

Contact links go to Sanifu. The footer says “Built in California, USA.” The icon toggles light/dark mode, starts from the system preference and remembers a choice. Motion can be paused, stops offscreen and respects reduced-motion preferences. All substantive content is available without JavaScript.

No build or automated tests were run for this update. Live deployment and browser acceptance are not claimed.

## Privacy and SMS terms

Owner-approved policy pages are served at `/privacy/` and `/terms/`. They cover sire.run and the is-optimized.com audit/report-delivery service; other products can have separate policies. Footer links make both pages discoverable. The approved disclosure and no-sale/no-marketing-sharing commitment are included. Publishing these pages does not activate SMS or establish campaign approval.
