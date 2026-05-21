# 坦克大战 (Tank Battle)

A classic Battle City-style tank game built with pure HTML5 Canvas and JavaScript. Zero dependencies.

## Play

Open `index.html` in any modern browser.

## Controls

| Key | Action |
|-----|--------|
| Arrow Keys | Move tank |
| Space | Shoot |
| P | Pause / Resume |
| M | Toggle sound |
| Enter | Start / Restart |

## Features

- 3 levels with escalating difficulty
- 3 enemy types: Basic, Fast, Heavy
- Destructible brick walls and indestructible steel walls
- Power-ups: Star (double shot), Tank (extra life), Bomb (clear enemies), Clock (freeze enemies), Shield (invulnerability)
- Procedural sound effects (Web Audio API)
- Retro pixel-art style rendered on Canvas

## Deployment (GitHub Pages)

1. Create a new GitHub repository (e.g., `tank-battle`)
2. Push this file to the `main` branch:
   ```
   git init
   git add index.html README.md
   git commit -m "Initial commit: Tank Battle game"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/tank-battle.git
   git push -u origin main
   ```
3. Go to repository **Settings → Pages**
4. Under "Source", select **Deploy from a branch** → `main` → `/ (root)` → Save
5. Game will be live at `https://YOUR_USERNAME.github.io/tank-battle/`

## License

MIT
