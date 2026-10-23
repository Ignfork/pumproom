# Pump Rooms ($PUMPROOMS)

A single-file site and game: `index.html`. There's no build step. Upload it to any static host (Vercel, Netlify, GitHub Pages).

## Edit before launch
Open `index.html` and find `CONFIG` at the top of the script:
- `xUrl` / `xHandle`: your X account. Until it's set, the Follow link shows a "coming soon" note.
- `ca`: the $PUMPROOMS mint address
- `launchUrl`: the pump.fun page

## What's in it
- A first-person backrooms you walk through: WASD to move, the mouse to look, E to use things, M for the map, ESC for the menu. On phones there's an on-screen joystick.
- Four levels, each with its own colours: Level 0 The Green (pump green), Level 1 Red Candle, Level 2 Moon Pool, Level 3 Rug Pit. Choose one from the menu, or walk through the EXIT door.
- Your room with a desk. Press E there to open PUMP TERM, a paper-trading terminal with a 10 SOL balance each round.
- 30-minute rounds that line up with the real clock. At the bell the lights go out and the balance resets.
- Something that stands at the end of the hall. It stalks you if you look away. Sanity drains in the dark. Almond water helps.

## Before launch
The coin feed and leaderboard are SIMULATED and labelled that way, and the pot reads "opens at launch".
Wiring in live pump.fun data and creator-fee payouts needs a backend; this static build doesn't include one.
