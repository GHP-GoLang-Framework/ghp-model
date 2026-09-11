# GHP Example

A minimal example project for [GHP](https://github.com/GHP-GoLang-Framework/ghp) — PHP-style templates, backed by real Go.

## Structure

- [`index.ghp`](index.ghp) → `/` — hub linking every page
- [`about.ghp`](about.ghp) → `/about`
- [`features.ghp`](features.ghp) → `/features` — branches, switches and loops
- [`docs/index.ghp`](docs/index.ghp) → `/docs`
- [`blog/index.ghp`](blog/index.ghp) → `/blog` — post listing
- [`blog/[slug].ghp`](blog/[slug].ghp) → `/blog/{slug}` — dynamic post page

## Running

Requires the `ghp` CLI ([build it from source](https://github.com/GHP-GoLang-Framework/ghp#installation) or use the Docker image).

```bash
ghp dev .     # starts a live-reload dev server
ghp build .   # generates the runnable Go module into ./build
```
