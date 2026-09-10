# WebLab

A lightweight browser playground for testing HTML, CSS, JavaScript, Three.js experiments, UI components, animations, canvas code and responsive layouts.

## Features

- Live HTML / CSS / JavaScript editors
- Sandboxed iframe preview
- Auto-run and manual Run controls
- Captured `console.log`, `info`, `warn`, errors and unhandled rejections
- Full / phone / tablet preview widths
- Starter presets for Three.js, UI components, forms, CSS motion, Canvas and responsive layouts
- Local autosave
- URL-based share state
- Standalone HTML export
- Mobile-friendly layout

## Local use

Open `index.html` through any static HTTP server. For example:

```bash
python3 -m http.server 8080
```

Then visit `http://localhost:8080`.

## Tests

Requires Node.js 22+:

```bash
node --test tests/*.test.mjs
```

## GitHub Pages

The included workflow tests the project and deploys the repository root with GitHub Pages on pushes to `main`.
