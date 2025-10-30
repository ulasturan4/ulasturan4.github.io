# Ulas Quarto Site (Starter)

## Quick start
1) Install Quarto: https://quarto.org/docs/get-started/
2) Put your portrait image at `images/profile.jpg` (replace with your own).
3) Replace placeholders in `_quarto.yml` and `index.qmd`:
   - `ulasnaki.turan@tu-dortmund.de`
   - `https://github.com/ulasturan4`
   - `REPLACE_SCHOLAR_URL` (or leave empty)
4) Preview locally:
   ```bash
   quarto preview
   ```
5) Build for GitHub Pages (outputs to `docs/`):
   ```bash
   quarto render
   ```
6) Deploy to GitHub Pages:
   - Create a repo, commit & push.
   - In GitHub → Settings → Pages: Source = `main`, folder = `/docs`.