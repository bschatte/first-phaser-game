# first-phaser-game

## Maze Blaster 3D

`index.html` is a one-level, first-person take on Maze Blaster, in the style of the original 1993 shooters. Open the file in a browser to play. No build step or server needed.

- **Level:** E1M1, Cardboard Keep. Find the blue key, beat the Cardboard King, flip the EXIT switch. One secret.
- **Weapons (keys 1-8):** Paper Popper, Confetti Needler, Comet Cannon, Glacier Blaster, Storm Chain, Cluster Rocket, Mega Bunny Beam, Origami Dragon.
- **Controls:** WASD to move, mouse or arrow keys to turn, click or Space to shoot, E to open doors, Shift to run, Tab for the map.

To edit the level, change the `MAP` grid near the top of the script. The legend is in the comment above it.

### Install it as an app

Once GitHub Pages is on, the game lives at https://bschatte.github.io/first-phaser-game/. Open that link and install it:

- **iPhone / iPad (Safari):** Share button, then **Add to Home Screen**.
- **Android (Chrome):** menu (three dots), then **Install app** or **Add to Home screen**.
- **Computer (Chrome or Edge):** click the install icon at the right end of the address bar.

It works offline after the first visit. When the game changes, bump `VERSION` in `sw.js` so installed copies pick up the update.
