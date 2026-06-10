# Markdown Studio

Markdown Studio is a browser-based markdown editor and previewer built as a single-page application in `index.html`.

## What it does

- Live Markdown editing with a real-time preview.
- Supports GitHub-flavored Markdown (GFM).
- Renders KaTeX math expressions.
- Renders Mermaid diagrams for flowcharts and diagrams.
- Supports emoji rendering via `marked-emoji`.
- Includes syntax highlighting with PrismJS.
- Contains a local-first experience: all rendering happens in the browser.

## Features

- editor and preview side-by-side layout
- focus mode and full-width preview mode
- find-in-preview search controls
- task list rendering
- math rendering with inline and block KaTeX
- Mermaid diagram rendering
- syntax-highlighted code blocks
- built with CDN dependencies only (no build step required)

## Preview

![Markdown Studio screenshot](./Screenshot%202026-06-10%20113337.png)

## How to run

1. Open `index.html` in your browser.
2. Start typing Markdown in the editor panel.
3. The preview updates automatically.

## Notes

- There is no backend server required.
- All libraries are loaded from CDN links inside `index.html`.
- The app is designed to work entirely locally in the browser.

## File

- `index.html` — the full application source and UI.

## License

This project is licensed under the MIT License. See the included `LICENSE` file for details.
