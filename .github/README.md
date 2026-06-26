# kevingriffin-new.github.io

Source for [kevingriffin-new.github.io](https://kevingriffin-new.github.io) —
my personal site (*Surveys, Sensors & Systems*).

Built with [Collards](https://collards.kingcons.io), a Common Lisp static site
generator, and deployed to GitHub Pages by GitHub Actions.

## How it works

- **`index.md`** — the homepage, a Collards Markdown page (`type: page`).
- **`.collards`** — site config (author, domain, title). The `:domain` value
  is what resolves asset URLs, so it must match the Pages host.
- **`assets/`** — static files, including `default.css` (the stylesheet the
  default page layout links to).
- **`.github/workflows/pages.yml`** — installs SBCL + Quicklisp, builds the
  Collards binary, runs `collards build`, and publishes `build/` to Pages.

The generated `build/` directory is **not** committed — CI regenerates it on
every push to `main`.

## Editing

Edit `index.md` (or add more `.md` pages / `assets/`), commit, and push to
`main`. The workflow rebuilds and redeploys. Pushing the `collards-ci` branch
runs the build only (no deploy), which is handy for checking a change before it
goes live.

> This README lives in `.github/` so the Collards build doesn't try to render
> it as a page.
