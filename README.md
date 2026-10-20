# Plucking Mango (JACA-NA-EMILIA)

Physics game built with [p5.js](https://p5js.org/) + [matter.js](https://brm.io/matter-js/) (internal title "Plucking Mango"): the player drags a stone to a slingshot, aims and releases it to knock down mangoes hanging from a tree. When a mango is hit, it stops being static and falls under gravity. The space bar puts the stone back on the slingshot for another try.

## Repository status

This repository is incomplete: `index.html` and `sketch.js` reference files that don't exist here — `libraries/matter.js`, `libraries/p5.js`, `libraries/p5.play.js`, the scripts `js/tree.js`, `js/stone.js`, `js/ground.js`, `js/mango.js`, `js/Stand.js`, `js/launcher.js`, and the images `images/boy.png` and `images/emilia.png`. The only commit in the history removed a template zip (`Project-C28-template-main.zip`) without those supporting folders ever being extracted/committed. As it stands, the page won't run without recreating these dependencies.

## Technologies

- [p5.js](https://p5js.org/) + [p5.play.js](https://p5play.molleindustria.org/) for drawing and sprites
- [matter.js](https://brm.io/matter-js/) as the physics engine (bodies, distance-based collision between stone and mangoes)
- Plain JavaScript, no build step

## Files present

- `sketch.js` — game logic: scene setup, stone/mango collision detection, mouse and keyboard controls
- `style.css` — basic canvas styling
- `index.html` — references libraries and helper scripts that are missing from the repository (see above)

## How to run

It can't be run as is: the libraries, the class scripts (`tree`, `stone`, `ground`, `mango`, `Stand`, `launcher`) and the images used in `sketch.js` are missing. Those folders (`libraries/`, `js/`, `images/`) would need to be recreated or recovered before opening `index.html`.
