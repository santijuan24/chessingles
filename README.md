# Rulebreaker Chess

A single-file chess game for the browser with four rule sets: **Classic**, **Atomic**, **Fog of War** and **King of the Hill**.
Play against the computer (Casual, Club, Master) or against a friend on the same screen.

## Run it

Open `index.html` in any modern browser. No build step, no dependencies.

## Rules

- **Atomic:** every capture explodes; the capturing piece and all non-pawn pieces on the 8 surrounding squares are removed. Kings cannot capture. Explode the enemy king to win.
- **Fog of War:** you only see your pieces and the squares they can move to. No check; capture the king to win.
- **King of the Hill:** standard chess, plus you win by moving your king to d4, e4, d5 or e5.
