# CarenBloom Website v3 — Redesign

## Background

- **v2** was deployed via Vercel (`carenbloom-site2/`) but taken down — flagged as too similar to another website.
- v3 is a ground-up redesign, not a patch.

## Current Status

- Ivan shared inspo sites (very different from each other and from v2).
- Direction unclear — need alignment from Ivan before building.

## Open Questions for Ivan

See `questions-for-ivan.md` for the draft message.

## Design Decisions (Locked In)

- **Background:** Cream (#F5F0E8)
- **Text:** Dark navy (#1A1A3E), light weight (200) for body, heavy (800) for emphasis
- **Accent 1:** Orange/coral (#FF7F5C) — "health" in hero, manifesto bg, bloom mark
- **Accent 2:** Blue (#2E4A8E) — "built." in hero, "now what?" text
- **Font display:** Unbounded (Google Fonts) — uppercase, mixed weights
- **Font body:** Outfit (Google Fonts)
- **Hero headline:** "The house that health built." — light/bold split
- **Bloom mark:** Original SVG logo, 15% opacity, slow rotation behind hero
- **Manifesto:** Orange (#FF7F5C) background, "now what?" white highlight + blue text + tilt animation, second line scroll-reveals word by word

## Page Structure (matching current site order)

1. ~~Hero~~ ✓
2. ~~Marquee~~ ✓
3. ~~Manifesto~~ ✓
4. Pillars (5 verticals)
5. Stats ($7.5T)
6. Portfolio (Hello Nancy + Biird)
7. Beliefs (stacked cards)
8. Ethos (values)
9. CTA + Form
10. Footer

## Working Files

- `flow-test.html` — current progress (hero + marquee + manifesto)
- `hero-bg5.html` — background comparison (picked #3 cream)
- `hero-final5.html` — font weight comparison (picked #1 light/bold)
- `hero-bloom.html` — bloom opacity tests
- `inspo.md` — inspo sites

## Decisions Log

| Date | Decision | Notes |
|------|----------|-------|
| 2026-07-20 | Start v3 planning | v2 taken down, redesign needed |
| 2026-07-24 | Font: Unbounded + Outfit | Geometric, personality, not serif |
| 2026-07-26 | Palette: cream bg + navy text + orange/blue accents | Avoids Elevator Goods similarity |
| 2026-07-26 | Hero: light/bold split, bloom mark behind | "The house that health built." |
| 2026-07-26 | Manifesto on orange bg | Scroll-reveal second line, "now what?" highlighted |
