# The Floor 🦞 — thefloor.dev

Static site. Single `index.html`, no dependencies, no build step.

## Deploy

### Local
```bash
cd site
python3 -m http.server 8000
```

### Cloudflare Pages
1. Push this `site/` directory to a repo
2. Cloudflare Pages → Create project → Connect repo
3. Build command: (leave empty)
4. Output directory: `site`
5. Custom domain: thefloor.dev

### Any static host
Just serve the directory. It's one HTML file.
