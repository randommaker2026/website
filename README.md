# website

Minimal personal homepage for **randommaker2026** — pure static HTML/CSS, no frameworks.

## Structure

```
website/
├── index.html      # Single page: hero, About, Contact
└── css/
    └── style.css   # All styles (mobile-first friendly)
```

## Local preview

Open `index.html` in a browser, or run:

```
python -m http.server 8000
```

## Deploy

GitHub Pages, deployed from the `main` branch via GitHub Actions (default static site workflow). Pushing to `main` redeploys automatically.
