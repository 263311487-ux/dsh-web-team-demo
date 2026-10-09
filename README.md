# DSH Team Demo

**Project role: demonstration / 演示项目.** This small page is retained as a browser-interaction example. For maintained browser acceptance tooling, see [dsh-verify](https://github.com/263311487-ux/dsh-verify); for the full project index, see [the portfolio catalog](https://github.com/263311487-ux/263311487-ux/blob/main/CATALOG.md).

This page is not a separate production product or a benchmark of general agent capability. A click demo does not establish complete accessibility or security coverage.

A tiny interactive demo page built by the web-team. The page is a single HTML document (`index.html`) with a linked stylesheet (`style.css`) and script (`app.js`), all working together to demonstrate simple DOM interactions.

## Features

- **Page title:** "DSH Team Demo" — a minimal single-page demo with a heading and two buttons.
- **Counter button (`#count-btn`):** Each click increments a counter and updates the button's label to `Clicked: N` (e.g. `Clicked: 1`, `Clicked: 2`, ...).
- **Color toggle button (`#color-btn`):** Each click toggles the `dark` class on the page body (`#page`), switching between light and dark themes.

## Files

- `index.html` — page structure and the two buttons
- `style.css` — styling, including the light/dark theme via the `dark` class
- `app.js` — click handlers for the counter and color toggle

## How to run

Open `index.html` in any modern web browser. No build step or server required.

## Try it

1. Click **Clicked: 0** repeatedly — the count increments each time.
2. Click **Toggle Color** — the page background flips between light and dark.
