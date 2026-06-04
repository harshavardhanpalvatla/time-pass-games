# Time Pass Games 🎮

A growing collection of browser-based games — no frameworks, no installs. Just open an HTML file and play.

---

## Games

### Connect 4 — Neon Arena (`connect4.html`)
A fully 3D Connect 4 game built with Three.js.

**Features**
- 3D board with metallic frame, torus cell rings, and neon edge glow
- Animated disc drops with bounce physics (GSAP)
- Particle burst + pulsing highlight on win
- Minimax AI with alpha-beta pruning (depth 8) — always blocks, always takes wins
- Main menu — Play vs CPU or Play vs Friend
- Procedural chiptune background music + SFX (Web Audio API)
- Dark neon theme, smooth animations

**How to play:** Open `connect4.html` in any modern browser. No server needed.

---

## Running locally

All games are single HTML files — just double-click or drag into a browser.  
CDN scripts (Three.js, GSAP) load from `jsdelivr.net`, so an internet connection is needed on first load.

---

## Adding a new game

1. Create `<game-name>.html` in the repo root
2. Add an entry to the Games section above
