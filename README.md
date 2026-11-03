# Snake Rival

Free single-file HTML5 snake battle. You (cyan) vs a smart AI snake (magenta) on a
neon 24x24 grid — eat glowing food to grow and score, first to 25 wins. Head-to-head
crashes go to the longer snake. One HTML file, zero assets.

**Play:** https://shuangyueliao.github.io/snake-rival/

- Arrow keys / WASD / swipe controls (2-turn input buffer, no accidental 180-degree turns)
- Three AI difficulties: reaction rate, planning depth (BFS + space lookahead), head-on caution
- 3-second respawns away from your rival, death-burst particles, pulsing food, WebAudio synth SFX, mute toggle
- Per-difficulty win/loss/draw record saved in localStorage
- Procedural graphics and sounds, no dependencies, no tracking, works offline once loaded
