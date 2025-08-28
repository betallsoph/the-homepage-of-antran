# The Homepage of An Tran

Static site with minimal styling and mock data for each page.

## Run locally

Option 1: VS Code Live Server
- Install "Live Server" extension
- Open `index.html` and click "Go Live`

Option 2: Python HTTP server

```bash
cd /Users/antt/Desktop/dev/the-homepage-of-antran
python3 -m http.server 5500
```

Then open http://localhost:5500/

## Structure
- `index.html` – homepage
- `styles.css` – site styles
- `bio.html`, `cv.html`, `portfolio.html`, `portfolio-creative.html`, `products.html`, `offer.html`, `contact.html`
- `mockdata/` – JSON files loaded by each page
