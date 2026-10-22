# ECHOES OF THE LAST STAR
A procedural 3D first-person narrative exploration game built with HTML, CSS, JavaScript and Three.js.

## Run it
Because the game uses JavaScript modules, open `index.html` through a local web server (recommended) rather than directly with `file://`:

```bash
python -m http.server 8000
```
Then visit `http://localhost:8000` and open the game.

It also works when deployed as a static site on Vercel or GitHub Pages. Three.js is loaded from jsDelivr, so an internet connection is needed on first load.

## Controls
- WASD / arrow keys: move
- Mouse: look around (click the game to recapture the pointer)
- Shift: sprint
- Space: jump
- E: interact
- Esc: pause
- Pause menu: cycle Performance / Balanced / Cinematic rendering profiles
- Auto-save every 5 seconds; Continue Journey restores your position, shard progress and choices
- Mobile: left virtual stick to move; drag the right side to look; tap the interaction prompt

## Game features
- A procedural 3D alien shore, observatory, shipwreck, ruins, crystals, starfield and particle motes
- Five collectible narrative memory shards
- Echo drone and Archivist NPC dialogue
- Choices that track trust, mercy and truth
- Three endings, unlockable after all five memories are recovered
- Procedural ambient audio using the Web Audio API
- Keyboard, mouse and mobile touch controls
- Fixed 60 Hz simulation steps to stabilize movement under variable frame rates
- Low-cost Performance profile by default, with adaptive resolution fallback for slow frame rates
- Sprint stamina meter and persistent save/resume
- No external 3D models or image assets; all world geometry is generated in code
