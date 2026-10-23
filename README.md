# Duescape: Design System

The working specification for Duescape, a subscription and budget tracker mobile app. Based on a client project (Netherlands). Brand name and data changed for confidentiality. Built as a single self-contained HTML page: no frameworks, no build step, every value taken from the Figma variables.

**Live demo:** https://tanyaaisen07-uiux.github.io/duescape-design-system/
**Tokens:** [`tokens.json`](tokens.json) (W3C Design Tokens format)

## At a glance
- 2 Figma variable collections: **Primitives** (single mode) and **Semantic** (Light and Dark)
- 28 semantic tokens, each an alias to a primitive, so switching mode retints a whole screen
- 17 type styles in Plus Jakarta Sans, tabular figures for money
- 4px spacing grid and an 8-step radius scale
- 36 components with their states, contrast measured to WCAG AA in both themes

## What's inside
- **Foundations:** primitive and semantic colour, typography, spacing and radius, data and currency formatting
- **Library:** buttons and chips, status badges, toggles and checkboxes, text and select fields, list rows, cards and charts, dialogs, bottom sheets, toasts, empty, error and loading states, icons and navigation
- **Rules:** accessibility (contrast table, touch targets, colour never the only signal), motion timings
- **Contribution:** how a new component is proposed, triaged, built and released without fragmenting the library
- **AI-readable system:** structured tokens, self-describing names and usage rules written as sentences, so people and AI assistants apply the system the same way
- **Developer tokens:** copy-paste CSS custom properties for both themes, plus `tokens.json`

## Author
Designed and documented by Tania Aisen, Product & UI/UX Designer
[Portfolio](https://tania-aisen.framer.website/) · [LinkedIn](https://www.linkedin.com/in/tania-aisen)
