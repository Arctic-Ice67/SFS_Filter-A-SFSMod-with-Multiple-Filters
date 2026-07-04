# SFS Filter

Real-time 2D post-processing effects for Spaceflight Simulator. Adds Bloom, Color Grading, Vignette, Chromatic Aberration, Color Balance, Depth of Field, Sharpen, and Lens Distortion — all configurable in-game via a ModGUI settings panel.

## Requirements

- Spaceflight Simulator 1.6.0 or newer
- [UITools](https://github.com/Neptune-Spaceflight-Simulator/UITools) mod installed

## Installation

1. Download `SFS_Filter.dll`
2. Place it in your SFS Mods folder
3. Launch the game and enter a world — the settings window will appear automatically

A default `Config.txt` is generated in the mod folder on first run.

## Effects

| Effect | Description |
|--------|-------------|
| **Bloom** | Soft glow from bright areas. Adjustable intensity, threshold, and diffusion spread |
| **Color Grading** | Saturation, contrast, and exposure correction in one pass |
| **Vignette** | Smooth darkening toward screen edges, with adjustable roundness |
| **Chromatic Aberration** | Per-channel RGB offset from screen center for a lens fringe effect |
| **Color Balance** | Independent RGB adjustment for shadows, midtones, and highlights with per-channel strength |
| **Depth of Field** | Tilt-shift blur — horizontal or vertical band with adjustable focus distance and range |
| **Sharpen** | 4-neighbor unsharp mask for crisp detail |
| **Lens Distortion** | Barrel/pincushion distortion with independent X/Y scale |

## Configuration

All settings can be adjusted through the in-game ModGUI window:

- **Per-effect toggles and sliders** — collapsible groups with `−`/`+` fine adjustment buttons
- **Save As** — export your settings as a named preset file
