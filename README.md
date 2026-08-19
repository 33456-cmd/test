# Arena Shooter

A small playable browser-based 3D FPS prototype built from scratch with Three.js primitives.

## Play

```bash
npm start
```

Open <http://localhost:5173>, click **PLAY**, then click the game view to lock the mouse.

## Controls

- `WASD` — move
- `Mouse` — look
- `Left Mouse` — automatic fire
- `R` — reload
- `Shift` — sprint
- `Space` — jump
- `Esc` — pause

## Goal

Survive five escalating enemy waves in the arena. Defeat robots to earn score. If your HP reaches zero, use **RESTART** to try again.

## Features

- Procedural low-poly arena made from simple geometry.
- Player movement, sprinting, jumping, mouse look, health, pause, and death.
- Automatic rifle with 30-round magazine, infinite reserve ammo, reload, recoil, muzzle flash, and hit effects.
- Robot enemies with multiple types, HP, speed, melee damage, and score rewards.
- Five-wave progression with win and death screens.
- Minimal HUD for HP, ammo, wave, score, and enemies remaining.
