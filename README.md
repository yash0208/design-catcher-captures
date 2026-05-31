# Design Catcher Captures

Public mirror of website captures from [Design Catcher](https://github.com/yash0208/design-catcher).

Each domain gets three markdown files:

| File | Description |
|------|-------------|
| `DESIGN.md` | Design system tokens — colors, typography, components |
| `STRUCTURE.md` | Page structure — sections, hero, animations, carousels |
| `UI-KIT.md` | Component library mapping — shadcn, Aceternity, Magic UI, 21st.dev |

## Browse

See [`index.json`](./index.json) for all captured domains.

```
captures/
  apple.com/
    meta.json
    DESIGN.md
    STRUCTURE.md
    UI-KIT.md
```

## Domain keys

Captures are keyed by registrable domain:

- `https://www.apple.com/macbook` → `apple.com`
- `https://apple.ca` → `apple.ca` (separate entry)

## Usage

Clone this repo and reference capture files in your AI agent prompts:

```
Implement the landing page using captures/apple.com/STRUCTURE.md and UI-KIT.md.
Follow DESIGN.md for all tokens.
```

## License

MIT — capture analysis only; not affiliated with captured websites.
