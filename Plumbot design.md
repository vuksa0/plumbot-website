# PlumBOT — Brand Guidelines

## Identity

**PlumBOT** is a bot/assistant product with a playful yet technical identity. The logo features a plum character with green leaf accents and a chat bubble motif (three dots).

---

## Typography

- **Primary Font**: Inter — versatile screen-optimized sans-serif with excellent legibility; feels clean and modern across all weights
- **Secondary Font**: IBM Plex Mono — reserved for code snippets, inline data, and technical UI elements only
- **Weight**: SemiBold (600) for headings and brand usage; Regular (400) for body copy
- **Brand Name Rendering**: `PlumBOT` — capital P, lowercase `lum`, capital `BOT`
- **Rationale**: Inter was designed specifically for screen interfaces — it pairs precision with approachability and scales well across all UI sizes

---

## Color Palette

| Name        | Hex       | Usage                                      |
|-------------|-----------|---------------------------------------------|
| Violet      | `#7C3AED` | Primary brand color, CTAs, links            |
| Deep        | `#0D0A1E` | Dark backgrounds, maximum contrast          |
| Iris        | `#DDD6FE` | Light accents, subtle backgrounds, dividers |
| Frost       | `#F5F3FF` | Light backgrounds, text surfaces            |
| Teal        | `#14B8A6` | Accent/highlight, success states, callouts  |

### CSS Variables

```css
:root {
  --color-violet: #7C3AED;
  --color-deep: #0D0A1E;
  --color-iris: #DDD6FE;
  --color-frost: #F5F3FF;
  --color-teal: #14B8A6;

  --font-brand: 'Inter', sans-serif;
  --font-mono: 'IBM Plex Mono', monospace;
}
```

---

## Logo Variations

Three approved logo lockups:

1. **Light** — Plum icon on lavender/off-white background
2. **Dark** — Plum icon on `#1C121B` dark background
3. **Color** — Full plum/purple background with white wordmark

Logo icon: plum fruit silhouette (purple, `#733B6D`) with green leaf and white chat bubble (three dots).

---

## Voice & Tone

- Technical but approachable
- Playful bot personality
- Inter's screen-optimized design signals precision and dev-friendliness without feeling cold

---

## Do's and Don'ts

**Do:**
- Use Inter for all brand and UI typography
- Use IBM Plex Mono strictly for code, data, and technical text elements
- Render the name as `PlumBOT` (never `Plumbot`, `PLUMBOT` in prose, or `plumbot`)
- Maintain the violet/deep/iris/frost/teal palette strictly

**Don't:**
- Use generic sans-serif fonts (Roboto, Arial, Open Sans) — these lack the design intentionality of Inter
- Introduce colors outside the defined palette without approval
- Separate the leaf from the plum in logo usage
- Use the teal accent as a primary color — it is a supporting highlight only
