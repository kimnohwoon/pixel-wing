# PIXEL WING

A small retro arcade shooter that runs in any mobile browser. One hand, portrait screen.

- **Move**: drag anywhere on the screen (arrow keys / WASD on desktop)
- **Fire**: automatic
- **BOMB**: the round button at the bottom right — clears incoming fire and damages everything on screen
- Pick up `P` (weapon power 1→3), `S` (shield) and `G` (score gems)
- Clear the wave set and a boss with an HP bar appears; beat it to reach the next stage
- 3 lives, combo multiplier, best score kept in the browser (`localStorage`)

## Tech

Single self-contained `index.html` — Canvas 2D with a fixed 390×844 playfield scaled to the
device, Web Audio API for 8-bit sound effects (mutable, top-right), requestAnimationFrame
loop with delta timing. Pixel fonts (Press Start 2P, Silkscreen) are self-hosted under
`fonts/` with their SIL Open Font License files.

The page is `noindex, nofollow` and contains no personal information.
