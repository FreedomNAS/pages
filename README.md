# pages

The FreedomNAS website, published by Codeberg Pages at
<https://freedomnas.codeberg.page/>. The documentation lives at
<https://freedomnas.codeberg.page/freedomnas-docs/>, built from
[freedomnas-docs](https://codeberg.org/FreedomNAS/freedomnas-docs).

The site is plain HTML and CSS: `index.html`, `style.css` and `assets/`.
Every push to `dev` publishes them through
`.forgejo/workflows/pages.yml`, which copies those files to `_site/` and
hands them to [git-pages/action](https://codeberg.org/git-pages/action) on
the self-hosted runner. The repository has to be called `pages` for the site
to sit at the root of `freedomnas.codeberg.page`.

To look at it locally, open `index.html` in a browser.

## License

Mozilla Public License 2.0, in `LICENSE`.
