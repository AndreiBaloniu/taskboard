# Goblin Colosseum

A small browser-based 3D roguelike arena prototype.

## Concept

You fight waves of kindergarten-sized goblins in a stone colosseum. There are no weapons. After every cleared wave, you choose one reward: rest for HP or take a permanent upgrade.

## Controls

- WASD: move
- Mouse: aim
- Left mouse button: punch
- Space: dash
- F: restart run

## Run locally

Use any static server from the project root.

```bash
npx serve .
```

or

```bash
python -m http.server 5173
```

Open `http://localhost:5173`.

## Assets

All assets are procedural and included in source:

- low-poly player model
- low-poly goblin model
- colosseum arena
- sand floor
- columns and walls
- hit particles
- UI panels

No external art files are required. Three.js is loaded from CDN.
