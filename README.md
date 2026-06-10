# Telmo Barros — Personal Website

Welcome to my hometown — Porto, Portugal. This is the repository for my gamified personal website, where you explore a top-down pixel map of the city and enter buildings to navigate through my resume.

Inspired by [Ariel Roffié's personal website](https://arielroffe.quest/).

## Running locally

Requires a simple HTTP server (direct `file://` access blocks Phaser's CDN script on some browsers).

```bash
# Python
python -m http.server 8080

# Node
npx serve .
```

## Controls

| Input | Action |
| --- | --- |
| Arrow keys / WASD / Mouse | Move |
| Touch & drag | Move (mobile) |
| E | Enter nearby building |
| Mouse click / Touch | Enter building |
| G | Toogle coordinates display |

## Credits

- **Map image** — AI generated with [Gemini](https://gemini.google.com/)
- **Built with** [Phaser 3](https://phaser.io/), HTML, CSS
- **AI assistance** — [Claude](https://claude.ai/) (Anthropic)
