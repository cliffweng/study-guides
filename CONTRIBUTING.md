# Contributing

This repository is the landing page for the study-guide collection. It is not a curriculum.

- **One page.** `index.md` lists the guides. Do not add per-topic pages here; those belong in each guide's own repository.
- **Live links only when the guide is actually up.** Use the real `https://cliffweng.com/.../` URL. Coming soon entries are plain text with a Coming soon label — never a guessed or 404 URL.
- **Blurbs stay one line.** Say what the guide is for. Do not paste its roadmap onto this page.
- **Do not add a `CNAME`.** `cliffweng.com` already serves the sibling guides. This site stays at `/study-guides/`.
- **Out of scope:** search backends, auth, a CMS, and changes to the cliffweng.com home app.
- **Local preview:**
  ```bash
  bundle install
  bundle exec jekyll serve
  ```
  Then open `http://127.0.0.1:4000/study-guides/`.
