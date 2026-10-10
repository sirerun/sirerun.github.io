# Sire Run corporate website

Static GitHub Pages site. No dependencies or build step. `index.html` contains the layout, styles and interactions. The original Sire mark is in `assets/brand/sire-logo.svg`. Product visuals are labeled placeholders.

## Publish

Push these files to the publishing branch, then select that branch and `/ (root)` in repository Settings → Pages → Deploy from a branch. `CNAME` specifies `sire.run`; the owner configures DNS. Enable HTTPS in Pages once the domain is verified and the certificate is available. No GitHub Pages settings or DNS changes were made by this implementation.

## Edit

Product copy and links are semantic HTML in `index.html`. The mosaic is decorative; keep substantive content in the readable product sections. Replace placeholder art with approved screenshots when available and update its labels. The nine additional projects are in a native disclosure. Theme preference is saved locally; continuous motion respects reduced-motion preferences and can be paused.

Implementation was authored in an isolated DGX directory. No build or automated tests were run. Publication and browser acceptance remain unverified.
