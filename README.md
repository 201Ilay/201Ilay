# Spin Tracker

A mobile web app for tracking roulette spins. Tap each number as it comes up and it suggests two bets:

- **Small bet**: an outside bet (red/black, odd/even, 1–18/19–36, or a dozen) based on what has been hitting most in your look-back window.
- **Big bet**: five neighbouring pockets on the wheel that have been hitting most, with your big stake split across them (35:1 each).

It also shows hot numbers, sleepers, dozen and column counts. Stakes, look-back size and European/American wheel are in settings. Spins are saved in your browser.

Run it: open `index.html` in any phone browser (no build step), or serve the folder with GitHub Pages.

Each spin is independent and the house edge applies to every bet; the suggestions follow patterns in the spins you entered and do not change the odds.
