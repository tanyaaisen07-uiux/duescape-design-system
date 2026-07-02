# Duescape — Design System

A living style guide extracted from the **Duescape** mobile app — a subscription & budget tracker. Built as a single self-contained HTML page: no frameworks, no build step, just design tokens and live components.

**Live demo:** https://tanyaaisen07-uiux.github.io/duescape-design-system/
**Product case study:** https://YOUR-SITE.framer.website

<!-- Add a screenshot: drag an image into this file on GitHub and it will insert the markdown for you -->

## What's inside

- **Design Principles** — Clarity First, Action Over Analysis, Familiar by Default; each mapped to the components that implement it
- **Color** — full palette with a Light / Dark theme switch; brand colors stay stable, surfaces adapt
- **Typography** — 8-step type scale (Inter / SF Pro), tabular figures for money
- **Geometry** — radius scale (16 / 14 / 12 / pill) and a 4px spacing grid
- **Components** — gradient balance card, action tiles, category icons, payment rows, info chips, settings rows, buttons, badges, toggle, tab bar, charts — all rendered live from the same CSS variables
- **Iconography** — line icons, 1.5–2px stroke, three sizes, container rules
- **Component in Context** — components shown on a mini Dashboard mock with an explanation of the role each one plays
- **Developer tokens** — copy-paste CSS variables for both themes

## How it works

The entire system runs on CSS custom properties defined in `:root` and overridden in `[data-theme="dark"]`. Every component on the page reads from these tokens, so switching the theme re-skins the whole guide — including the phone mock — without any additional styles.

```css
:root       { --bg:#F1F3F8; --surface:#FFFFFF; --text-1:#0E1320; ... }
[data-theme="dark"] { --bg:#0A0D16; --surface:#121624; --text-1:#F5F7FA; ... }
```

## Note on accuracy

Color values were extracted from mockup screenshots and are close approximations. Verify against the source Figma file before shipping to production.

---

Designed & documented by **Tania Aisen** · [Portfolio](https://YOUR-SITE.framer.website)
