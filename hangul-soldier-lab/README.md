# Hangul Soldier Lab — 류 RYU-01

One Hangul letter — 류 (ㄹ five strokes + ㅠ three strokes, eight total) — stood upright as a soldier. A single self-contained HTML page: a live character lab where every stroke of the letter is a piece of gear.

- **Open `index.html` directly in a browser.** No build step, no dependencies.
- **Language:** auto-detects browser locale (Korean for `ko`, English otherwise); header toggle or press `L`. Choice persists.
- **Controls:** pose (들고 Present / 경례 Salute / 차렷 Attention / 행진 March), helmet, weapon, armor + visor colors, stroke weight (체급 build), letter width, drag-to-slant, backgrounds (ops grid / night / taegeuk / transparent), glow, march speed.
- **Keyboard:** `1–4` pose · `R` randomize · `G` jamo skeleton guides · `M` sound · `L` language.
- **Export:** SVG, PNG (1280×1360), clipboard SVG, live JSON config — all from the current state.

## Anatomy note

ㄹ becomes the armor block (helmet / chest / chin guard, the two empty cells are the visor opening and armor gap); ㅠ becomes the limb frame (arms from the long horizontal, legs and boots from the verticals). With the rifle held level, the character reads as 류 exactly — the "jamo integrity" gauge is honest: 100% in Present, less when the pose breaks the letterform.

## Branch policy

Lives on its own branch (`ryu-01-hangul-soldier-lab`) inside WikaTayo; not merged to main.

## Roadmap sketches (not built)

- More jamo soldiers: ㅁ and the other nasal/simple-final family.
- A Baybayin soldier (same stroke-is-skeleton method, different script).
- A 無 (Mu) soldier.

Built 2026-11-23.
