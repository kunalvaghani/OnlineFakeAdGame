# Commando Squad Runner (HTML5)

An endless three-lane runner made with **Phaser 3**. Collect coins, choose +/× gates, dodge mines, grab power-ups, buy cosmetics, and defeat the boss. Includes safe soft-restart that avoids Phaser “sys” errors, reactive synth SFX/music, difficulty options, and persistent progress via `localStorage`.

## Live Demo
**Live Demo:** https://kunalvaghani.github.io/OnlineFakeAdGame/

## Features
- Phaser 3.60 (CDN) – no build step
- Coins, power-ups (Magnet/Shield/Slow-mo), combo meter
- Cosmetic shop (player skins & visual themes)
- Boss phase with telegraphed attacks
- Pause, volume, motion, haptics toggles
- **Safe restart** that cancels timers/tweens & restarts cleanly
- Progress saved in `localStorage`

## Controls
- **Arrow Left/Right** or **A/D** – switch lanes  
- **Mouse/Touch:** tap/drag left/right thirds  
- **P:** Pause / Resume  
- **R:** Restart (from Pause or Result)

## Run locally
Just open `index.html` or use a tiny server:
```bash
# Python 3
python -m http.server 5500
# then visit http://127.0.0.1:5500/index.html
