<div align="center">

<img src="https://raw.githubusercontent.com/drunkleen/leenium.webpage/refs/heads/master/assets/LEENIUM.png" width="250" alt="Leenium logo" />

**A dark Waybar theme built from the shared Leenium palette.**

Hosted under `github.com/drunkleen/leenium.waybar`.

<img src="./assets/preview.png" width="95%" alt="Leenium Waybar preview" />

</div>

---

## Features

- **Floating layout** - pill modules, floating surfaces, and soft borders instead of a flat strip
- **Shared palette** - uses the same Leenium colors across the ecosystem
- **Waybar-friendly CSS** - a single importable stylesheet with common widget coverage
- **Low-glare UI** - restrained highlights and muted inactive states

---

## Color Palette

| Role | Hex | Swatch |
|---|---|---|
| Background | `#0b1113` | ![](https://placehold.co/16x16/0b1113/0b1113.png) |
| Panel | `#11191c` | ![](https://placehold.co/16x16/11191c/11191c.png) |
| Popup | `#182326` | ![](https://placehold.co/16x16/182326/182326.png) |
| Line / Border | `#223033` | ![](https://placehold.co/16x16/223033/223033.png) |
| Active | `#304144` | ![](https://placehold.co/16x16/304144/304144.png) |
| Selection | `#365156` | ![](https://placehold.co/16x16/365156/365156.png) |
| Foreground | `#d8e3e0` | ![](https://placehold.co/16x16/d8e3e0/d8e3e0.png) |
| Muted | `#718688` | ![](https://placehold.co/16x16/718688/718688.png) |
| Accent (Teal) | `#33b8a8` | ![](https://placehold.co/16x16/33b8a8/33b8a8.png) |
| Cyan | `#59d6c5` | ![](https://placehold.co/16x16/59d6c5/59d6c5.png) |
| Emerald | `#4dba7a` | ![](https://placehold.co/16x16/4dba7a/4dba7a.png) |
| Sea Bright | `#67cf94` | ![](https://placehold.co/16x16/67cf94/67cf94.png) |
| Type | `#71e4d8` | ![](https://placehold.co/16x16/71e4d8/71e4d8.png) |
| Warn | `#d9c76b` | ![](https://placehold.co/16x16/d9c76b/d9c76b.png) |
| Warn Bright | `#efd45e` | ![](https://placehold.co/16x16/efd45e/efd45e.png) |
| Orange | `#f4a259` | ![](https://placehold.co/16x16/f4a259/f4a259.png) |
| Error | `#e16f73` | ![](https://placehold.co/16x16/e16f73/e16f73.png) |
| Error Soft | `#f08787` | ![](https://placehold.co/16x16/f08787/f08787.png) |
| Blue | `#5e9bff` | ![](https://placehold.co/16x16/5e9bff/5e9bff.png) |
| Void | `#020405` | ![](https://placehold.co/16x16/020405/020405.png) |
| Sidebar | `#0e1518` | ![](https://placehold.co/16x16/0e1518/0e1518.png) |
| Card | `#141e21` | ![](https://placehold.co/16x16/141e21/141e21.png) |
| Floating | `#1d2a2d` | ![](https://placehold.co/16x16/1d2a2d/1d2a2d.png) |

---

## Install

1. Copy `style.css` and `config.jsonc` into your Waybar config directory.

```bash
mv ~/.config/waybar ~/.config/waybar.backup
git clone https://github.com/drunkleen/leenium.waybar.git ~/.config/waybar
```

2. Restart Waybar.

```bash
pkill waybar
waybar &
```

---

## Use

Use `config.jsonc` and `style.css` together for a floating, rounded bar.

### File layout

```text
~/.config/waybar/
  config.jsonc
  style.css
```

### Recommended modules

- `workspaces`
- `clock`
- `network`
- `pulseaudio`
- `battery`
- `tray`

---

## The Leenium Ecosystem

Leenium is a unified dark desktop environment built around the shared palette. Explore the full ecosystem at [leenium.drunkleen.com](https://leenium.drunkleen.com).

<img src="https://raw.githubusercontent.com/drunkleen/leenium.webpage/refs/heads/master/assets/footer.png" width="100%" alt="Leenium footer" />

<p align="center">
    Copyright &copy; 2026-present <a href="https://github.com/drunkleen" target="_blank">LEENIUM</a>
</p>
<p align="center">
    <a href="https://github.com/drunkleen/leenium.webpage/blob/master/LICENSE">
        <img src="https://img.shields.io/static/v1.svg?style=for-the-badge&label=License&message=MIT&logoColor=d9e0ee&colorA=365156&colorB=33B8A8"/>
    </a>
</p>