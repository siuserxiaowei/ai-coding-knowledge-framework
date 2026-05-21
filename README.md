# AI Coding Knowledge Framework

Static GitHub Pages version of the AI engineering discipline knowledge framework.

## V2 Pages

- `index.html`: version selector and compact 16-source ledger.
- `research.html`: recommended research archive layout.
- `magazine.html`: editorial long-scroll layout.
- `blueprint.html`: engineering blueprint console layout.
- `assets/v2.css`: shared visual system.
- `scripts/build-v2-pages.mjs`: source-of-truth generator for all four pages.

## Validation

- `npx --yes html-validate index.html research.html magazine.html blueprint.html`
- Each page includes 16 source links with `target="_blank"` and `rel="noopener noreferrer"`.
- The generated pages do not include tracking scripts.
