## Cursor Cloud specific instructions

This is a static HTML landing page project for the FreeReader iOS app. There are no build tools, package managers, or external dependencies.

### Running the dev server

Serve the site locally with Python's built-in HTTP server:

```
python3 -m http.server 8080
```

Then open `http://localhost:8080/` in Chrome.

### Key notes

- The entire site is a single self-contained `index.html` (inline CSS, no JS, no external assets besides `icon.png`).
- There is no lint, test, or build step — the project has zero dependencies.
- The iOS app source code is **not** in this repository; this repo is only the marketing landing page.
