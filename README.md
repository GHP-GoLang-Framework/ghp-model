# GHP Example

A minimal example project for [GHP](https://github.com/GHP-GoLang-Framework/ghp) — PHP-style templates, backed by real Go.

## Structure

- [`index.ghp`](index.ghp) → `/`
- [`docs/index.ghp`](docs/index.ghp) → `/docs`

## Running

Requires the `ghp` CLI ([build it from source](https://github.com/GHP-GoLang-Framework/ghp#installation) or use the Docker image).

```bash
ghp dev .     # starts a live-reload dev server
ghp build .   # generates the runnable Go module into ./build
```
