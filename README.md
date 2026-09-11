# Degraded

A dark, minimal manga reader for **PC and mobile**.

**Owner:** ShamblesRK

## Features

- Browse popular, latest, ongoing, and completed manga
- Real covers and chapters via the MangaDex API
- Full reader (vertical scroll + paged mode)
- Keyboard controls on PC (← → Space Esc)
- Custom title font (Another Danger) with blue glow + glitch
- Settings & About menu
- Responsive layout (works on desktop and phone)

## How to use on PC

### Option 1 – Open directly
Just double-click `index.html`

### Option 2 – Local server (recommended)
```bash
# Python
python -m http.server 8080

# or Node
npx serve .
```
Then open http://localhost:8080

### Option 3 – GitHub Pages
1. Upload this folder to a GitHub repository
2. Settings → Pages → Source: main / root
3. Site will be live at `https://yourusername.github.io/repo-name/`

## Structure

```
degraded/
├── index.html
├── favicon.svg
├── fonts/
│   ├── AnotherDanger.otf
│   └── AnotherDanger-Slanted.otf
└── README.md
```

## Notes

- Not affiliated with MangaDex
- Title font: Another Danger (demo)
- Built for personal use by ShamblesRK
