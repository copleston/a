# Arcade Satire

A deliberately over-the-top, unofficial arcade-style parody. The page loops
through three full-screen messages, showing each for exactly one second. It is
designed for a 4:3 arcade-cabinet display but scales cleanly on phones and
modern screens.

## Run locally

Requires Node.js 22.13 or newer on Linux.

```bash
npm ci
npm run dev
```

## Build

```bash
npm run build
```

The static browser files are written to `dist/client`.

## Publish

The workflow in `.github/workflows/pages.yml` builds and publishes the site on
every push to `main`. See [GITHUB_PAGES.md](GITHUB_PAGES.md) for the one-time
GitHub Pages and Namecheap domain settings.

This project is an unofficial parody and is not affiliated with Red Bull or
Monster Energy.
