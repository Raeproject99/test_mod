# Tokyo Night for Zen

A Sine mod that retones Zen Browser's UI with the [Tokyo Night](https://github.com/enkia/tokyo-night-vscode-theme) palette by enkia.

## What it does

Zen's `zen-theme.css` builds nearly every UI color from two roots — `--zen-primary-color` and `--zen-branding-dark` — via `color-mix()` chains. This mod redefines those roots to Tokyo Night's `#7aa2f7` blue and `#1a1b26` background, then directly overrides the handful of variables (main browser background, urlbar, dialog, popup panel, etc.) that hardcode their own `light-dark()` values.

Color scheme is pinned to dark — Tokyo Night is fundamentally a dark theme.

## Preferences

Open the mod's settings panel in Sine to choose:

- **Accent color** — blue (default), purple, cyan, teal, green, orange, or red. Each maps to a Tokyo Night syntax role.
- **Storm variant** — switches the backgrounds from `#1a1b26` (Night) to the slightly lighter, blue-tinted `#24283b` (Storm).

## Palette reference

| Role            | Hex       |
|-----------------|-----------|
| Background      | `#1a1b26` |
| Sidebar / panel | `#16161e` |
| Input field     | `#14141b` |
| Foreground      | `#a9b1d6` |
| Comment / muted | `#565f89` |
| Border          | `#414868` |
| Blue            | `#7aa2f7` |
| Cyan            | `#7dcfff` |
| Teal            | `#73daca` |
| Purple          | `#bb9af7` |
| Green           | `#9ece6a` |
| Yellow          | `#e0af68` |
| Orange          | `#ff9e64` |
| Red             | `#f7768e` |

## Install (local)

1. Drop this folder into your Zen profile's `chrome/` directory (or wherever Sine watches for local mods on your install).
2. In Zen, open Settings → Sine and add the mod by folder name.
3. Pick your accent under the mod's settings. Restart isn't required for preference changes.

## Credits

- Tokyo Night palette: [enkia/tokyo-night-vscode-theme](https://github.com/enkia/tokyo-night-vscode-theme) (MIT)
- Built for [Sine](https://github.com/CosmoCreeper/Sine) on [Zen Browser](https://zen-browser.app/)
