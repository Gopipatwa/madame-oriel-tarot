# Madame Oriel's Tarot

A candlelit tarot reading game. You shuffle by hand, choose from all 78 cards, and a reader turns them with pauses,
probing questions and combination readings. Single file, no build step, no dependencies.

## Run locally
Open `index.html` in a browser. (Sound starts after you tap Enter.)

## Deploy on GitHub Pages
1. Create a new repository on GitHub (public).
2. Upload `index.html` (and this README) to the repository root.
3. Go to **Settings > Pages**. Under **Build and deployment**, choose **Deploy from a branch**, branch `main`, folder `/ (root)`, then Save.
4. After a minute your game is live at `https://<your-username>.github.io/<repo-name>/`.

## Notes
- The live conversation (Claude-written replies) only works inside Claude. On GitHub Pages it hides itself and the
  reader uses the built-in script, so the game plays fully.
- Fonts load from Google Fonts. Offline, the page falls back to Georgia.
- To add live AI replies outside Claude, call the Claude API from a small backend you control. Never put an API key in this file.
