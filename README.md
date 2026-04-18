# Ghosterized

> ⚠️ **Early preview.** Colors may still shift between versions.

A **light** theme for [Ghostty](https://ghostty.org) based on the classic [Solarized Light](https://ethanschoonover.com/solarized/) palette by Ethan Schoonover.

Companion to [Intelirized](https://github.com/htulibacki/intelirized) — same palette, same readability goals, now in your terminal.

## Installation

Drop the `ghosterized` file into Ghostty's user themes directory:

```sh
mkdir -p "$HOME/.config/ghostty/themes"
cp ghosterized "$HOME/.config/ghostty/themes/ghosterized"
```

This path works on both macOS and Linux.

### Activate

Add to `~/.config/ghostty/config`:

```
theme = ghosterized
```

Reload with **Cmd+Shift+,** (macOS) or **Ctrl+Shift+,** (Linux).

## Palette

Canonical Solarized Light mapping — same base colors as Intelirized:

| Role | Hex |
| --- | --- |
| Background | `#fdf6e3` (base3) |
| Foreground | `#657b83` (base00) |
| Cursor | `#586e75` (base01) |
| Selection | `#eee8d5` (base2) |

ANSI accents: yellow `#b58900`, orange `#cb4b16`, red `#dc322f`, magenta `#d33682`, violet `#6c71c4`, blue `#268bd2`, cyan `#2aa198`, green `#859900`.

## License

[MIT](LICENSE) © Hubert Tulibacki
