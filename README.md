# Cypress Bayou Trail

A top-down bayou maze game built with Phaser 3, starring Little Eli.

Cross the boardwalk maze through the swamp, dodge the alligator and the cottonmouths, cross the bridge to the hidden deck, and watch a squirrel mistake a sunbathing corn snake for part of the branch. Then follow the orange ribbons back to the car.

## Play it

Open `index.html` in a browser, or serve the folder with any static file host (GitHub Pages works well). The game is a single self-contained HTML file: all sprite images are embedded in the file itself. The only thing it loads from the internet is the Phaser library from a CDN, so it needs a connection the first time it opens.

## Controls

- **Computer:** Arrow keys or WASD to walk, E or Space to talk and read signs.
- **Phone:** A Game Boy style control deck under the game screen. Hold the D-pad to walk, tap A (or B) to talk and read. Tap the Full button at the top right for full screen landscape play, and Restart for a fresh start from the car.

## About

- World: a 2560 by 2560 boardwalk maze with one winding route to the clearing, signed dead ends, a midway checkpoint, and a bridge that is the only way onto the deck.
- Hazards: one alligator that lunges across the trail and three patrolling cottonmouths. Getting caught costs a heart and sends you back to the last checkpoint.
- Art: every character and animal is a hand-drawn pixel sprite sheet made for this game, including Little Eli, based on a photo of the author at age two.
