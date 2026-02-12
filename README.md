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
