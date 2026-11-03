# Snake Rival — Store Submission Materials

## Short description (CrazyGames / GameDistribution / itch.io, <=200 chars)

Duel a smart AI snake on a neon 24x24 grid. Eat glowing food to grow and score —
first to 25 wins. Head-to-head crashes go to the longer snake. Three AI levels.

(160 chars — verified, under the 200 limit)

## Details

- Genre: Arcade / Action / Snake
- Controls: Arrow keys / WASD on desktop; swipe gestures on mobile (2-turn input
  buffer prevents accidental 180-degree turns). M = mute via on-screen button.
- Features: real-time dual-snake battle, BFS-pathfinding AI with danger avoidance
  and tail-chase fallback, three difficulty levels (reaction rate / planning depth /
  head-on caution), 3-second respawns, win/loss records per difficulty saved in
  localStorage, neon glow visuals with death-burst particles, procedural WebAudio
  sounds (eat / death / respawn / victory) with mute toggle.
- Rules: 24x24 shared arena, 3-5 pulsing food orbs on the field, eat = +1 point and
  grow; hitting walls, your own body or the rival's body is fatal; head-to-head
  collisions are won by the longer snake (equal length = both die). First to 25
  points wins the match.
- Tech: Vanilla JavaScript, Canvas, WebAudio. Single-file HTML5 (no external
  assets, no CDN, no fonts, no tracking), works offline once loaded. Fixed-step
  game clock (120ms tick, gently tuned down as the leading score rises).

## Tags

snake, arcade, battle, duel, ai, casual, neon, single-file, mobile-friendly

## CrazyGames submission checklist
- [x] Self-contained index.html (SDK loads only on crazygames domains)
- [x] gameplayStart / gameplayStop / happytime wired (plus loadingStart / loadingStop in loader)
- [x] Responsive (square board scales to viewport, portrait & landscape)
- [x] No external links inside gameplay, no analytics
- [ ] Cover: cover-16x9.png (1280x720)
- [ ] Screenshots: screenshot-raw.png (1280x800)

## GameDistribution
- Upload: snake-rival-gd.zip (contains index.html only)

## itch.io
- Upload: snake-rival-itch.zip, mark "This file is playable in browser",
  entry file: index.html, viewport embed: fits any size (board scales), kind: html
- Pricing: $0 (donations optional)
