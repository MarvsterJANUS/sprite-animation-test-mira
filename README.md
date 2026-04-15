# sprite-animation-test-mira

A browser-based sprite animation preview tool for the **Mira** character — a chibi-style doctor/scientist. Supports multiple animations with per-animation settings, adjustable playback, and live quality rendering.

## Animations

| Name | Sprite Sheet | Grid | Frames |
|---|---|---|---|
| Idle |  | 10×9 | 67 (0–66) |
| Explaining |  | 9×9 | 75 (0–74) |
| Greeting |  | 10×10 | 93 (0–92) |

## Usage

1. Clone the repo
2. Place the sprite sheet PNGs in the root folder (pulled automatically via Git LFS)
3. Open  in a browser — no build step or server required

\
## Features

- **Animation selector** — switch between Idle, Explaining, and Greeting with one click; settings auto-update per animation
- **Playback controls** — play/pause, step forward/backward, reset
- **Adjustable FPS** — 1–60 fps slider, default 30 fps
- **Scale slider** — resize the preview without losing quality (0.05×–1×)
- **Frame range** — isolate a subset of frames to loop a specific clip
- **Background swatches** — dark, black, white, green screen, and checkerboard
- **HiDPI rendering** — canvas buffer uses  for sharp output on retina displays

## Sprite Sheet Format

All sprite sheets use the same frame size: **1080×1920 px per frame**, arranged left-to-right, top-to-bottom. The last row may contain fewer frames than the column count.

## Requirements

- Any modern browser (Chrome, Firefox, Edge, Safari)
- Git LFS — required to pull the PNG sprite sheets

\Updated Git hooks.
Git LFS initialized.