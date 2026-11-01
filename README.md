# kaits-site

The KAITS website, served at https://kyte-school.github.io/kaits-site/ by GitHub Pages.

To move it to kaits.maic.club: add a CNAME record `kaits` → `kyte-school.github.io` (DNS only) where maic.club's DNS is hosted, then add a `CNAME` file containing `kaits.maic.club` and set the custom domain in the repo's Pages settings.

A single static page (`index.html`) with the brand mark in `assets/`. No build step: edit and push to `main`.

To show the demo button, set `CONTACT.email` near the bottom of `index.html`.
