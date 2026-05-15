# Simple static site (Cloudflare Pages)

This is a no-build static website: plain HTML + CSS.

## Replace placeholders
- `assets/headshot.jpg` (add your photo)
- `files/cv.pdf` (add your CV)

## Local preview
Open `index.html` in a browser, or run a tiny server:

- Python: `python3 -m http.server 8000`
- Then visit http://localhost:8000

## Deploy (Cloudflare Pages)
Connect this repo in Cloudflare Pages. Use:
- Build command: (leave empty)
- Output directory: `/` (root)
