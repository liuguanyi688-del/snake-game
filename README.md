# Snake Game

A single-file browser snake game built with HTML, CSS, and JavaScript. It is simple enough to read in one sitting, but complete enough to show canvas rendering, keyboard control, scoring, collision detection, and restart flow.

## Features

- Canvas-based game board.
- Keyboard-controlled snake movement.
- Food spawning and score tracking.
- Best score display.
- Wall and self-collision game over logic.
- Restart button.
- No build tools and no dependencies.

## Run Locally

Open `index.html` in a browser.

Or from PowerShell:

```powershell
cd D:\sjk\snake-game
start .\index.html
```

## Project Structure

```text
snake-game/
├─ index.html   # HTML, CSS, and JavaScript in one file
└─ README.md
```

## Why This Project Is Useful

This is a compact frontend practice project. It demonstrates the basic loop used by many browser games:

1. Read input.
2. Update game state.
3. Detect collisions.
4. Render the next frame.
5. Repeat on a timer.

## Deployment

Because it is a static single-file project, it can be deployed directly with GitHub Pages, Vercel, Netlify, or any static file server.
