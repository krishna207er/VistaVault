# VistaVault

VistaVault is a plain HTML/CSS/JS image-search app: you type a topic, hit Search, and results appear as a responsive grid of image cards. This repository currently contains the Part 1 UI scaffold — the search box, suggestion chips, empty-state grid, and theming are all in place, but no images are fetched yet (that arrives in Part 2).

## Design decisions

1. **Teal-and-sand palette instead of the reference purple** — I wanted a calm, outdoorsy feel that matches the "explore the world" tagline, and a light/dark mode pair implemented purely in CSS variables so the theme toggle needs no JavaScript.
2. **A 5-chip quick-pick row** — so users can jump to common topics (Nature, Cities, Animals, Food, Space) in one click instead of typing, which lowers the barrier to a first search.
3. **Sticky header + left-aligned single-column layout** — the brand and search stay reachable while scrolling, and left-aligning the panel (rather than centring everything) gives the grid room to breathe on widescreens while still re-flowing to 2–3 columns on phones.
