# Aanu Oshakuade — Single-page site

Minimal serif-driven personal page with a soft three.js point cloud background, inspired by clean editorial layouts.

## Local preview
```bash
python3 -m http.server 8000
# visit http://localhost:8000
```

## Deploy to GitHub Pages
1) Create a repo on GitHub named `aanuoshaks` (or your choice).
2) Push this directory:
```bash
git add .
git commit -m "Initial site"
git branch -M main  # if your repo uses main
git remote add origin git@github.com:aanuoshaks/aanuoshaks.git
git push -u origin main
```
3) In GitHub, go to **Settings → Pages** and set source to `Deploy from a branch`, select branch `main` and folder `/ (root)`.

## Customization notes
- Fonts: heading uses Cormorant Garamond; body uses Source Serif 4. Update in `<head>` if you prefer another pairing.
- Point cloud palette is teal/charcoal/mint; tweak in the `palette` array in `index.html`.
- Background haze and spacing live in the CSS `body` and `.wrap` rules.
