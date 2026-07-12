# homer

An interactive reference and companion to Homer's Iliad and Odyssey, bringing together characters, places, events, themes, and their connections in an accessible, searchable experience.

**The Wine-Dark Sea** is a single, self-contained web page — all styles and
scripts are inlined, with no external dependencies or build step.

## View it

**Live:** https://bip-river.github.io/homer/ *(once GitHub Pages is enabled — see below)*

**Locally:** open `index.html` in any modern browser (double-click it, or drag it
into a browser window). Nothing to install.

### Getting around

- Browse by character, place, event, or theme from the home page.
- Press `/` to jump straight to search.
- Follow the "journey" view to trace the narrative.

## Publishing (GitHub Pages)

This repo includes a workflow (`.github/workflows/pages.yml`) that deploys the
site on every push to `main`. To turn it on, do this once:

1. Go to the repository's **Settings → Pages**.
2. Under **Build and deployment → Source**, choose **GitHub Actions**.

The next push to `main` (or a manual run of the "Deploy to GitHub Pages" workflow)
will publish the site to https://bip-river.github.io/homer/.

## License

[MIT](LICENSE)
