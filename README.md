# Red Floor

A top-down room-clearing shooter that runs in the browser. Clear each floor of the building room by room, keep the hostages alive, and move on to a tougher layout.

**Play:** open `index.html` in a browser, or enable GitHub Pages for this repo (Settings → Pages → deploy from `main`, root).

## Controls

| Action | Keys |
|---|---|
| Move | `W` `A` `S` `D` or arrow keys (walk into a door to kick it in) |
| Aim and shoot | Mouse, hold the left button to fire |
| Switch gun | `1` to `7`, or the mouse wheel |
| Flashbang | `F` or right-click, thrown at the crosshair |
| Reload / pause | `R` / `P` |
| Touch | Drag the left side to move, hold the right side to fire |

## Guns

Silenced pistol, revolver, SMG, shotgun (also blows doors open), assault rifle, sniper rifle (goes through several hostiles) and machine gun.

## What's in a floor

- **Line of sight:** you only see what your operator can see; rooms you haven't entered stay dark.
- **Doors:** kicking one in stuns whoever is behind it.
- **Flashbangs:** three per floor; they daze hostiles who see the blast.
- **Explosive barrels:** shoot them to blow up everything nearby, including other barrels.
- **Hostages:** touch one to secure it (+100). Shooting one costs 150.
- **Noise:** gunfire wakes hostiles in nearby rooms. The silenced pistol barely does.

A single self-contained HTML file: no build step, no dependencies.
