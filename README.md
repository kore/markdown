# Kore's Markdown Viewer

A single-file, fully self-contained Markdown editor and viewer. Just open `markdown.html` in a browser — no build step, no server, no installation.

Deployed at https://k023.de/markdown.html

## Features

- **Live editing** with GitHub Flavored Markdown support (tables, checklists, fenced code blocks)
- **Syntax highlighting** via highlight.js (bash, yaml, dockerfile, + auto-detect)
- **Export** to PDF and Word (.doc)
- **Open / Save** `.md` files directly
- **Persistent** — content is saved to `localStorage` automatically
- **Drag & drop** `.md` files onto the editor
- **Keyboard shortcuts** — `Ctrl+E` toggle edit/view, `Ctrl+S` save, `Ctrl+O` open
- **Print-friendly** styles

## Dependencies (all loaded from CDN)

| Library | Purpose |
|---|---|
| [marked](https://github.com/markedjs/marked) | Markdown parsing |
| [highlight.js](https://highlightjs.org/) | Code syntax highlighting |
| [html2pdf.js](https://github.com/eKoopmans/html2pdf.js) | PDF export |
| [FileSaver.js](https://github.com/eligrey/FileSaver.js) | File download |
| [Bootstrap Icons](https://icons.getbootstrap.com/) | UI icons |

## Usage

Open `markdown.html` in any modern browser. That's it.
