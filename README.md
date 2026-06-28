# 💗 Hipster Pink for Zed

A neon-pink-on-black retheme of [1ay1's Hipster Green Theme](https://github.com/1ay1/hipster-green-zed-theme).
Same terminal-inspired structure, swapped to a vibrant magenta/pink palette with full UI, terminal and syntax coverage.

The extension ships **three variants** that share one identical palette and differ **only** in the color used for strings, so you can pick the string accent that reads best for you:

| Variant | String color |
| --- | --- |
| **Hipster Pink Cyan** | `#5DE0E6` |
| **Hipster Pink Lavender** | `#B98AFF` |
| **Hipster Pink Peach** | `#FFA07A` |

All three appear as separate entries in the Zed theme selector.

## Color Palette

- **Background (editor/UI)** `#0b070a` — deep near-black
- **Base text** `#FF1493` — deep pink
- **Primary accent** `#FE019A` — cursor, active borders, focus
- **Secondary accent** `#FF8AD4`
- **Elevated surface** `#1a0e16` — menus, active tab, hover
- **Muted text** `#7d4a63` — line numbers, secondary text

### Syntax

- **keyword** `#FF10F0` · **function** `#FE019A` · **number / constant** `#FF6EC7`
- **type** `#FF77FF` · **variable** `#FFB3DE` · **operator / punctuation** `#D98AB8`
- **comment** `#7d4a63` · **string** *(varies per variant — see table above)*

### Terminal (ANSI)

`red #FF3B6B` · `green #50C878` · `yellow #FFD166` · `blue #6EC1FF` · `magenta #FE019A` · `cyan #5DE0E6`
(bright/dim slots are derived as lighter/darker shades of each base.)

### Git status

`added #50C878` · `modified #FFD166` · `deleted #FF3B6B`

## Installation

### Manual Installation
1. Clone or download this repository
2. Place `themes/hipster-pink.json` in `~/.config/zed/themes/`
3. Open the Theme Selector (`Cmd+K Cmd+T`) and pick one of the three **Hipster Pink** variants

Zed watches that folder, so edits to the JSON apply live on save — no restart needed.

## Credits

Forked from the **Hipster Green Theme** by **Ayush Bhat ([1ay1](https://github.com/1ay1))**, itself a port of Tabby/iTerm2's Hipster Green color scheme. Pink retheme and multi-variant split by this fork.

## License

MIT License (unchanged from upstream — see `LICENSE`). Feel free to modify and share!

---

*Neon pink terminal* 💗
