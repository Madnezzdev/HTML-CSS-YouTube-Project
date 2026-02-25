# YouTube Homepage Clone (HTML/CSS)

A simple, responsive clone of the YouTube home page built for practicing modern CSS layout techniques (Flexbox, Grid, positioning) with clean, modular styles.

## Overview
- Static front‑end only — no frameworks, no JavaScript logic.
- Fixed header and sidebar, responsive video grid, and simple UI details like tooltips and notification badges.
- Additional sandbox pages demonstrate individual layout concepts.

## Folder Structure
- `youtube.html` — main page
- `styles/`
  - `general.css` — global resets, typography, page padding
  - `header.css` — fixed header, search, icons, tooltips
  - `sidebar.css` — fixed left sidebar and link styling
  - `video.css` — responsive video grid and card layout
- `Icons/` — UI icons and sample profile image
- `Thumbnails/` — sample video thumbnails
- `Channelpfp/` — sample channel profile pictures
- Sandbox pages:
  - `flexbox.html` — Flexbox practice
  - `grid.html` — Grid practice
  - `position.html` — Positioning practice

## Features
- Fixed header with search, mic, app, upload and notification controls (with tooltip hover).
- Fixed left sidebar with common YouTube sections.
- Responsive video grid:
  - 2 columns ≤ 750px
  - 3 columns 751–999px
  - 4 columns ≥ 1000px
- Clean, accessible typography using Google Fonts (Roboto).

## How to Run
- Quick open: double‑click `youtube.html` in your file explorer, or:
  - PowerShell:
    ```powershell
    start .\youtube.html
    ```
- Optional local server (recommended for consistent paths):
  - PowerShell:
    ```powershell
    cd "c:\Users\Tomas\OneDrive\Desktop\html-css-js-SQL-course\Youtube"
    python -m http.server 5500
    ```
    Open http://localhost:5500/youtube.html in your browser.

## Customize
- Change grid breakpoints/columns in `styles/video.css` (media queries).
- Adjust header/tooltip behavior in `styles/header.css`.
- Replace images in `Icons/`, `Thumbnails/`, and `Channelpfp/` with your own assets (keep filenames or update paths in HTML).

## Notes
- This project is for educational purposes only. YouTube names and logos are trademarks of their respective owners.
- No build step or dependencies required.
