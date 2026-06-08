<div align="center">

# f22-raptor-sim

### F-22 Raptor Combat Simulator — Operation Eastern Shield.

[![▶ Play Now](https://img.shields.io/badge/%E2%96%B6%20PLAY-in%20your%20browser-6b46c1?style=for-the-badge)](https://cognis-digital.github.io/f22-raptor-sim/)
[![License: COCL 1.0](https://img.shields.io/badge/License-COCL%201.0-2b6cb0.svg)](LICENSE)

**▶ Play instantly: https://cognis-digital.github.io/f22-raptor-sim/**  · no install, runs in any modern browser.

</div>

## About
F-22 Raptor Combat Simulator — Operation Eastern Shield. Built as a self-contained browser experience (HTML5 + JS canvas/WebGL). Part of the [Cognis Digital](https://cognis.digital) labs.

`mermaid
flowchart LR
  P[Player] --> B[Browser / GitHub Pages]
  B --> E[HTML5 + JS engine]
  E --> R[Render loop · input · audio]
`

## Run locally
```bash
git clone https://github.com/cognis-digital/f22-raptor-sim.git && cd f22-raptor-sim
python -m http.server 8000   # then open http://localhost:8000
```

## License
COCL v1.0 — see [LICENSE](LICENSE).
