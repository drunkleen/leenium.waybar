<div align="center">

# Leenium Waybar

<img src="./assets/icon.png" width="120" alt="Leenium Waybar logo" />

**A dark Waybar theme built from the shared Leenium palette, tuned closer to Omarchy than to a flat accent theme.**

Hosted under `github.com/drunkleen/leenium.waybar`.

<img src="./assets/preview.png" width="100%" />

</div>

---

## Color Palette

| Role | Hex | Swatch |
|---|---|---|
| Background | `#0b1113` | ![](https://placehold.co/16x16/0b1113/0b1113.png) |
| Sidebar | `#0e1518` | ![](https://placehold.co/16x16/0e1518/0e1518.png) |
| Panel | `#11191c` | ![](https://placehold.co/16x16/11191c/11191c.png) |
| Card | `#141e21` | ![](https://placehold.co/16x16/141e21/141e21.png) |
| Popup | `#182326` | ![](https://placehold.co/16x16/182326/182326.png) |
| Floating | `#1d2a2d` | ![](https://placehold.co/16x16/1d2a2d/1d2a2d.png) |
| Hover | `#223033` | ![](https://placehold.co/16x16/223033/223033.png) |
| Active | `#304144` | ![](https://placehold.co/16x16/304144/304144.png) |
| Selection | `#365156` | ![](https://placehold.co/16x16/365156/365156.png) |
| Foreground | `#d8e3e0` | ![](https://placehold.co/16x16/d8e3e0/d8e3e0.png) |
| Muted | `#718688` | ![](https://placehold.co/16x16/718688/718688.png) |
| Cyan | `#59d6c5` | ![](https://placehold.co/16x16/59d6c5/59d6c5.png) |
| Teal | `#33b8a8` | ![](https://placehold.co/16x16/33b8a8/33b8a8.png) |
| Emerald | `#4dba7a` | ![](https://placehold.co/16x16/4dba7a/4dba7a.png) |
| Blue | `#5e9bff` | ![](https://placehold.co/16x16/5e9bff/5e9bff.png) |
| Yellow | `#d9c76b` | ![](https://placehold.co/16x16/d9c76b/d9c76b.png) |
| Orange | `#f4a259` | ![](https://placehold.co/16x16/f4a259/f4a259.png) |
| Red | `#e16f73` | ![](https://placehold.co/16x16/e16f73/e16f73.png) |

---

## Features

- **Omarchy-like layout** - pill modules, floating surfaces, and soft borders instead of a flat strip
- **Shared Leenium palette** - uses the same palette source of truth as the rest of the ecosystem
- **Waybar-friendly CSS** - a single importable stylesheet with common widget coverage
- **Low-glare UI** - restrained highlights and muted inactive states

---

## Install

1. Copy `style.css`and `config.jsonc` into your Waybar config directory.

```bash
mv ~/.config/waybar ~/.config/waybar.backup
git clone https://github.com/drunkleen/leenium.waybar.git ~/.config/waybar
```

2. Restart Waybar.

```bash
pkill waybar
waybar &
```

### Sample config

Use `config.jsonc` and `style.css` together for a more Omarchy-like setup.

### File layout

```text
~/.config/waybar/
  config.jsonc
  style.css
```

---

## Use

Recommended module setup:

- `workspaces`
- `clock`
- `network`
- `pulseaudio`
- `battery`
- `tray`

The theme is designed to feel closer to Omarchy's rounded, floating bar than to a minimal flat accent bar.

---

## The Leenium Ecosystem

Leenium is a unified dark desktop environment built around the same color palette. Alongside this Waybar theme, the project ships matching configs for:

- [**VS Code**](github.com/drunkleen/leenium.vscode) - editor theme and UI palette
- [**Neovim**](github.com/drunkleen/leenium.nvim) - syntax highlights and UI elements
- [**Firefox**](github.com/drunkleen/leenium.firefox) - browser theme extension
- [**OpenCode**](github.com/drunkleen/leenium.opencode) - terminal-first theme
- [**Omarchy**](github.com/drunkleen/leenium.omarchy) - desktop theme bundle

Visit [github.com/drunkleen](https://github.com/drunkleen) or [leenium.drunkleen.com](https://leenium.drunkleen.com/) to explore the full setup.

---

## License

MIT © [Leenium](LICENSE)
