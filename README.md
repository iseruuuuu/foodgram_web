# FoodGram Web

This is the static landing/intro site for FoodGram. It consists of `index.html` and `styles.css`, with image assets under `docs/`.

## What’s included
- Hero section (app summary, store badges)
- App intro images (`docs/introduce*.png`)
- Feature grid
- Highlights (chips and bullet list)
- Premium plan section
- Official accounts links
- Responsive layout and mobile navigation (hamburger)

## Directory structure
```
.
├── index.html
├── styles.css
└── docs/
    ├── icon.png
    ├── introduce.png
    ├── introduce2.png
    ├── introduce3.png
    ├── introduce4.png
    └── introduce5.png
```

## Run locally
- Simply open `index.html` in your browser.
- If you prefer a local server (for relative paths/CORS consistency), use one of these:

```bash
# Python
python3 -m http.server 5173
# or
# Node (npx)
npx serve .
```

Then open `http://localhost:5173` (or the displayed URL). VS Code’s Live Server extension also works.

## Tech stack
- HTML5 (`index.html`)
- CSS (`styles.css`)
- A tiny bit of vanilla JavaScript (mobile nav toggling)
- No dependencies, no build step

## Deploy
Host on any static hosting service (e.g., GitHub Pages, Vercel, Netlify).

- GitHub Pages example (publishing from the `main` branch root)  
  1. Go to Repository Settings → Pages  
  2. Select Branch: `main`, Folder: `/ (root)`  
  3. Save and wait a few minutes for it to go live

## Screenshot
![App overview](docs/introduce.png)

## Meta
- Title: FoodGram | Eat x Photo x Share
- Description: A new food social app to discover delicious meals through photos
- Favicon/App Icon: `docs/icon.png`

## License
© 2025 FoodGram. All rights reserved.

## Contributing
Before opening an Issue/PR, a brief discussion about the approach is appreciated.
