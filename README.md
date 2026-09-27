# Study Guides

The public directory of Cliff Weng study guides: Engineering / CS, Finance, and Founders. One landing page, with a one-line blurb for each guide. Topic pages stay in each guide's own repository.

**Live site:** https://cliffweng.com/study-guides/

GitHub Pages publishes the same site at https://cliffweng.github.io/study-guides/ once Pages is enabled. Do not add a `CNAME`. `cliffweng.com` already serves the sibling guides, and this repo stays on the path above.

## Enabling GitHub Pages

Just the Docs is configured via `_config.yml` (`remote_theme: just-the-docs/just-the-docs`). After this lands on `main`:

1. Repo **Settings → Pages**.
2. **Build and deployment → Source**: **Deploy from a branch**.
3. Branch: `main` / folder: `/ (root)`.
4. Save. The first build often takes a few minutes.
5. Site publishes to https://cliffweng.github.io/study-guides/

GitHub Pages allows `jekyll-remote-theme`, which is what `remote_theme` in `_config.yml` uses. The expected public path on the existing host is https://cliffweng.com/study-guides/.

## Local preview

```bash
bundle install
bundle exec jekyll serve
```

Then open `http://127.0.0.1:4000/study-guides/`.

## How to contribute

See [CONTRIBUTING.md](CONTRIBUTING.md). In short: this repo is the directory only. When a guide goes live, add its real `https://cliffweng.com/...` URL and a one-line blurb. Coming soon entries stay plain text.

## License

[MIT](LICENSE)
