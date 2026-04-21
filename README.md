# Clief Notes — Competition Submissions

Marcos Accioly's entries for the [Clief Notes](https://cliefnotes.com/) community weekly competitions.

Each competition has its own folder with a self-contained submission (single-file HTML + source notes), deployed via GitHub Pages.

## Submissions

| # | Challenge | Folder | Live |
|---|-----------|--------|------|
| 01 | Brand voice guide — Ruff Cuts (mobile dog grooming) | [`competition-01/`](./competition-01/) | [View](https://marcosaccioly.github.io/cliefnotes-competition/competition-01/) |

## Structure

Each `competition-NN/` folder contains:

- `index.html` — the submission artifact (self-contained, no build step)
- `brief-decoded.md` — brief analysis
- `angle.md` — author angle lock
- `content.md` — draft of the deliverable
- `system.md` — AI system layer (when applicable)
- `favicon.svg`, `og-image.{svg,png}` — assets

## Local preview

```bash
cd competition-01
python -m http.server 8000
# open http://localhost:8000
```

## License

Submissions are authored by Marcos Accioly. Reuse of the method is encouraged; credit appreciated.
