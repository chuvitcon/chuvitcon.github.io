# Nga Nguyễn — Portfolio
Live: https://chuvitcon.github.io

## Local Preview
Double-click `index.html` — works offline, no build step needed.

## Structure
```
chuvitcon.github.io/
├── index.html
├── README.md
└── assets/
    └── images/
        ├── 1.gif  →  20.gif/png   (work slides)
        └── about.jpg              (REPLACE: your photo)
```

## Placeholders to replace in index.html
| Marker | What to put |
|--------|-------------|
| `<!-- REPLACE: your photo -->` | `<img class="about-photo" src="assets/images/about.jpg" alt="Nga Nguyễn">` |
| `<!-- REPLACE: Project XX caption -->` | Real project name / year |
| `data-email="your@email.com"` | Your real email |
| `<!-- REPLACE: your Instagram -->` | Instagram URL + handle |
| `<!-- REPLACE: your LinkedIn -->` | LinkedIn URL |

## Deploy to GitHub Pages

```bash
cd "C:\Users\TienNguyenQuoc\Documents\Antigravity\Website Portfolio"
git init
git remote add origin https://github.com/chuvitcon/chuvitcon.github.io.git
git add .
git commit -m "🎨 init portfolio"
git branch -M main
git push -u origin main
```

Then go to:
**https://github.com/chuvitcon/chuvitcon.github.io/settings/pages**
→ Source: Deploy from branch → `main` → `/ (root)` → **Save**

Site goes live at **https://chuvitcon.github.io** in ~1 minute.
