# Red Floor

A top-down room-clearing shooter that runs in the browser. Clear each floor of the building room by room, keep the hostages alive, and move on to a tougher layout.

**Play:** open `index.html` in a browser, or enable GitHub Pages for this repo (Settings → Pages → deploy from `main`, root) and play at https://francotaind.github.io/red_floor/.

## On an Android phone

1. Open https://francotaind.github.io/red_floor/ in Chrome.
2. Tap **Install app** on the title screen, or Chrome's menu → **Add to Home screen** / **Install app**.
3. Launch Red Floor from the home screen: it opens full-screen in landscape and keeps working offline after the first load.

Phone controls: left thumb moves, right thumb aims (push further to fire, with a little aim assist). The three buttons on the right swap gun, throw a flashbang and reload. The camera follows you through the building, and arrows at the screen edge point to hostages you haven't reached.

## Controls

| Action | Keys |
|---|---|
| Move | `W` `A` `S` `D` or arrow keys (walk into a door to kick it in) |
| Aim and shoot | Mouse, hold the left button to fire |
| Switch gun | `1` to `7`, or the mouse wheel |
| Flashbang | `F` or right-click, thrown at the crosshair |
| Reload / pause | `R` / `P` |

## Guns

Silenced pistol, revolver, SMG, shotgun (also blows doors open), assault rifle, sniper rifle (goes through several hostiles) and machine gun.

## What's in a floor

- **Line of sight:** you only see what your operator can see; rooms you haven't entered stay dark.
- **Doors:** kicking one in stuns whoever is behind it.
- **Flashbangs:** three per floor; they daze hostiles who see the blast.
- **Explosive barrels:** shoot them to blow up everything nearby, including other barrels.
- **Hostages:** touch one to secure it (+100). Shooting one costs 150.
- **Noise:** gunfire wakes hostiles in nearby rooms. The silenced pistol barely does.

The game is a single HTML file with no build step. `manifest.webmanifest`, `sw.js` and `icons/` make it installable as a phone app and playable offline.
