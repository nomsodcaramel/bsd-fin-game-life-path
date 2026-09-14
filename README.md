# BSD Fin Game: ปีหนึ่งปี (life path prototype)

A playable prototype of the BSD Fin Game board as a road through one year. A life is a path, not a loop:
12 month stretches, month gates that everyone crosses together, and a road that ends at each player's own goal.
The winner is still decided by cash + savings, never by how far a pawn walked.

## Run

Plain HTML, CSS and JS in one file. No build step, no dependencies.

- Open `index.html` in a browser, or
- serve the folder: `python3 -m http.server 8000`, then open http://localhost:8000

Designed mobile-first at 390 x 844. Fonts load from Google Fonts (Quicksand, Inter, Kanit).

## Try it

1. Tap the roll key: the die lands, the pawn walks, the tile pulses, then the card rises.
2. Pick one of the two choices and watch the money move.
3. Tap `ข้ามไปสิ้นปี` to jump to the end of month 12 and see both goals and the look-back.

## Status

Prototype, not the shipped game. The demo players, goal amounts, allowance and the fast-forward's scripted
picks are placeholders, not content decisions. Brand colours, fonts, icons and the owl belong to BSD.

## Files

- `index.html` - the whole prototype
- `icons/` - tile, calendar, goal and finish icons
- `assets/owl-reading.png` - the card mascot
