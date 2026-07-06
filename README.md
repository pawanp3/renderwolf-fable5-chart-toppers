# 🕹️ Chart Toppers Arcade

Playable web remakes of the **top free iOS games** — 15 small, touch-first prototypes,
one folder per game, with original names and AI-generated art.

**▶ Live:** https://pawanp3.github.io/renderwolf-fable5-chart-toppers/

Each game reimplements only the *mechanic* of a chart-topping title (mechanics aren't
copyrightable) under an original name, with freshly generated art — no trademarked
names, characters, or logos. Built with **Fable 5** · **Renderwolf**.

## Games

| Game | Plays like |
|------|-----------|
| Purrfect Logic | number-logic (sudoku), cat theme |
| Combo Grid | drop-block line clears |
| Carnival Cannon Crush | physics smash |
| Slide & Exit | color-sort slide puzzle |
| Starlight Peaks | tri-peaks solitaire |
| Star Gulp | grow-a-hole swallow |
| Vector Vacate | slide-the-arrows escape |
| Perfect Season Draft | lineup drafting |
| Bluff Circle | social deduction / imposter |
| Drift Away Arrows | one-line paint-the-board |
| Sudden Death Strikers | penalty shootout |
| Last Keep | aim-and-defend |
| Seaside Scoop | merge-to-rebuild |
| Circle Down | shrinking-circle survival |
| Blocky Obby Dash | obstacle-course runner |

## Run locally

```sh
python3 -m http.server 8000
# open http://localhost:8000  (the arcade launcher)
# on your phone, same Wi-Fi:  http://<your-computer-ip>:8000
```

Every game is a single static HTML file (vanilla JS + canvas) — portrait, touch-first,
no build step. Art is pre-baked into each game's `assets/`, so nothing but static files
is served.
