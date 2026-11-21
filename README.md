# Domino Pyramid - Shift Pyramid

A solo domino puzzle that runs entirely in the browser. Place all 28 double-six dominoes on a pyramid where every touching number must match, then use the Shift Pyramid mode to keep solving after the pyramid is complete.

Open `index.html` in any modern browser. The whole game is one file with no dependencies, no build step and no accounts.

## How to play

- The pyramid has 28 positions. Rows from the bottom hold 7 horizontal, 6 vertical, 5 horizontal, 4 vertical, 3 horizontal, 2 vertical and 1 horizontal tile.
- Select a tile from the tray, then tap or click any empty position. Both orientations are tried automatically. If neither fits every existing neighbour, the placement is refused.
- Tiles can be placed above gaps.
- Click any placed tile to return it to the tray; the other tiles stay untouched.
- Finish checks the whole pyramid.
- Keyboard: Tab and Enter to select or place, F to change the orientation preference. Flip preference only matters when both orientations fit.

## Shift Pyramid

With a tile selected, click or tap the small left or right arrow beside the seven-tile base. The working pyramid shifts one position: the selected tile enters on one side, turned automatically to match the exposed base end, and only the opposite fringe tiles return to the tray. All surviving tiles stay exactly where they are, even above gaps.

- Hover or focus an arrow to preview which tiles would return before shifting.
- Each complete shift is one Undo operation.
- Shifts can be repeated without limit.
- After a completed pyramid, return any tile to select it and continue shifting.

## Features

- Undo for every placement and shift
- Sound effects (optional, synthesized locally)
- Full screen mode
- Enlarge board option on small screens, with horizontal scrolling
- Local Hall of Fame stored on the device
- Responsive layout for phones and desktops, touch friendly

## Files

- `index.html` - the current game (v0.2.2, Shift Pyramid)
- `index.html.old` - the original v0.1.3 Domino Pyramid, kept for reference

## Status

Features above are described from the source code; the game has not been tested end to end. There is no license file yet.
