# Bystander Studio — Portfolio

Personal portfolio of **Tricia Siez** — a tech-savvy Virtual Assistant (admin · social media · content · data).

Static site, no build step. `index.html` is the landing page.

| Page | Purpose |
|------|---------|
| `index.html` | Home — hero, toolkit, selected work |
| `about.html` | About / profile |
| `resume.html` | Printable résumé (also exported to `portfolio/assets/resume.pdf`) |

All media lives in `portfolio/assets/`.

## Local preview

Open `index.html` directly, or serve the folder:

```bash
npx serve .
```

## Deploy

Any static host works (Vercel, Render, Netlify, GitHub Pages). No framework, no environment variables — point the host at the repo root and serve `index.html`.
