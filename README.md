# Neurodiverse Aotearoa

Static site for [neurodiverse.nz](https://neurodiverse.nz), published with GitHub Pages.

## Structure

- `index.html` — homepage
- `about/index.html` — About Alistair
- `workshops/index.html` — ADHD workshops for teachers and parents
- `contact/index.html` — contact form
- `tools/index.html` — free classroom tools, served at `/tools/`
- `tools/spelling-test.html` — Schonell Graded Word Spelling Test
- `tools/checkin-wheels.html` — EF / ASD student check-in wheels
- `assets/` — stylesheet (`style.css`), logo files and favicon
- `CNAME` — tells GitHub Pages this repo serves the `neurodiverse.nz` custom domain
- `sitemap.xml` / `robots.txt` — search engine discovery files

## Contact form

The form posts to Formspree. Create a free form at formspree.io, then replace `REPLACE_WITH_FORM_ID` in `contact/index.html` with your form ID. Until then the form shows a "not connected yet" message.

## Editing

Plain HTML and CSS, no build step. Edit directly and commit; GitHub Pages redeploys within a minute or two of a push to the default branch.
