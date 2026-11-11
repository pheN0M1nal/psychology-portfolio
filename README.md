# Rehab Ikhlaq — personal website

A single-page site (`index.html`), published with GitHub Pages.

Optional files, added next to `index.html`:

- `photo.jpg` — a portrait; it appears in the About section.
- `cv.pdf` — the CV; a "Download CV" button appears in the header once it's live, and the CV section links to it.
- `cv-preview.jpg` — thumbnail of the CV shown in the CV section. Regenerate it whenever `cv.pdf` changes.

Short links `/cv` and `/resume` open the PDF: `cv/` and `resume/` hold small redirect pages (for GitHub Pages), and `_redirects` does the same on Netlify.

To add another certification, search `index.html` for `CERTIFICATE`.
