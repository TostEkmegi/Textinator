# Textinator

A minimal, AI-powered text editor that runs in your browser. Write in markdown, get AI suggestions, open and save files — all from a single HTML file with no installation required.

![Status](https://img.shields.io/badge/status-early%20development-orange)

---

## What it is

Textinator is a distraction-free writing tool built around the Monaco editor (the same engine that powers VS Code) with a local AI hooked up to it. The idea is to keep things simple — just you, your writing, and an AI assistant that actually runs on your own machine.

No cloud, no subscriptions, no data leaving your computer.

## Features (so far)

- Clean markdown editor with a Solarized Light theme
- Open and save `.md` files from your filesystem
- Local AI integration via LM Studio
- No build tools, no npm, no setup — just open `index.html`

## What you'll need

- A modern browser (Chrome or Edge work best for file system access)
- [LM Studio](https://lmstudio.ai/) running locally with a model loaded and the local server turned on
- CORS enabled in LM Studio's server settings

## Getting started

1. Clone or download this repo
2. Open LM Studio, load a model, start the local server, and make sure CORS is enabled
3. Open `index.html` directly in your browser
4. Start writing

If you want to use a different local AI server, just change the URL in the `AskAi` function inside `index.html` to point to your server's endpoint.

## Roadmap

- [ ] Sidebar AI chat panel
- [ ] Inline AI suggestions (ghost text)
- [ ] Custom system prompt configuration
- [ ] Multiple tabs / documents
- [ ] Electron wrapper for a proper desktop app

## Built with

- [Monaco Editor](https://microsoft.github.io/monaco-editor/) — the editor component
- [LM Studio](https://lmstudio.ai/) — local AI inference
- Vanilla HTML, CSS, and JavaScript — nothing else

## Notes

This started as a learning project with near zero prior web development experience. It's rough around the edges but it works. Contributions and ideas welcome.

    ps: this markdown file was written compeletly within Textianor!
