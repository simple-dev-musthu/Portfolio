# Musthak Portfolio Website

A personal portfolio website for Muhammed Musthak, a Junior Web Developer and BCA student at Yenepoya University.

## Tech Stack

- **Languages**: HTML5, CSS3, Vanilla JavaScript
- **Build System**: None (static site)
- **Package Manager**: None
- **External Dependencies**: Google Fonts (Poppins), Font Awesome v6 (via CDN)

## Project Structure

```
.
├── index.html        # Main entry point (single-page portfolio)
├── Portfolio.css     # All styles and media queries
├── test-link.html    # Test/utility file
├── Pictures/         # All image and media assets
└── README.md         # Project documentation
```

## Running the App

The site is served using Python's built-in HTTP server:

```bash
python3 -m http.server 5000 --bind 0.0.0.0
```

The workflow "Start application" is configured to run this command on port 5000.

## Deployment

Configured as a **static** deployment with `publicDir: "."` — Replit serves the files directly with no build step needed.
