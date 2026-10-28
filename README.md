# ZBA: Zooted Basketball League

A small browser basketball game. No build step or package installation is needed.

## Run it

1. Unzip the folder.
2. Open a terminal in `ZBA-Zooted-Basketball-League`.
3. Run `python3 -m http.server 8000`.
4. Open `http://localhost:8000` in a browser.

The local server keeps the sprite sheet loading reliably and lets the game save progress in the browser. The optional pixel font loads from Google Fonts; the game still works with a system monospace font when offline.

## Files

- `index.html` — game and UI.
- `assets/players.png` — six reference-inspired pixel player sprites.

The supplied player artwork is kept intact—no mismatched limbs are drawn over it. Jumping, shot timing, dunk movement, and ball motion remain animated; matching art frames can add more character-specific poses.

## Controls

Move with WASD or the arrow keys. Hold Shift to sprint; Space jumps; E shoots; Q crosses or steals; R hesitates; F performs a step-back; Esc pauses.
