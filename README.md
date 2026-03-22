# laurensGM.github.io
Product Management Portfolio of Laurens Goormachtigh.
This portfolio was created with the help of the instructions in the Coursera project Create Your UI/UX Portfolio with GitHub.
I used the bootstrap template called 'devfolio' which can be found here: https://bootstrapmade.com/
I removed the blog section from the template.

## Performance

Load time has been improved by:
- **Deferring scripts** so the page can render before JS runs.
- **Preloading the hero image** so it starts loading immediately.
- **Lazy-loading** below-the-fold images (about, portfolio, testimonials) so they load only when near the viewport.
- **Preloader timeout**: the spinner hides after 2 seconds max so slow connections don’t wait forever.

**Further improvement (recommended):** Compress large images. The hero (`assets/img/budva.jpg`) and about photo (`assets/img/laurens2.jpg`) are ~1.3 MB and ~1.7 MB. Resize to ~1200–1600px wide and compress (e.g. with [Squoosh](https://squoosh.app/) or `cwebp`) to bring each under ~200–300 KB for much faster first load.

## Contact form (Formspree)

The contact section uses a form that sends submissions to your email via [Formspree](https://formspree.io/) (free tier). To enable it:

1. Sign up at [https://formspree.io/register](https://formspree.io/register).
2. Create a new form and set your email as the recipient.
3. Copy your form ID (e.g. `xyzabcde` from `https://formspree.io/f/xyzabcde`).
4. In `index.html`, find `action="https://formspree.io/f/FORM_ID"` in the contact form and replace `FORM_ID` with your form ID.

## Featured case study (Alliance Bioversity & CIAT)

Content lives in `portfolio-single-featured.html`; the portfolio card is first on `index.html`.

**Images:** put files in `assets/img/portfolio-bioversity-ciat/` — see `README.md` in that folder (`hero.jpeg`, `figure-02.jpeg`). Replace the placeholder JPEGs with your real visuals; keep filenames or update HTML paths.
