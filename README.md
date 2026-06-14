<div align="center">

# fpv-strike-drone

### FPV Strike Drone — first-person drone flight & strike sim.

[![▶ Play Now](https://img.shields.io/badge/%E2%96%B6%20PLAY-in%20your%20browser-6b46c1?style=for-the-badge)](https://cognis-digital.github.io/fpv-strike-drone/)
[![License: COCL 1.0](https://img.shields.io/badge/License-COCL%201.0-2b6cb0.svg)](LICENSE)

**▶ Play instantly: https://cognis-digital.github.io/fpv-strike-drone/**  · no install, runs in any modern browser.

</div>

## Usage — step by step

1. Play instantly in any modern browser — no install: <https://cognis-digital.github.io/fpv-strike-drone/>
2. To run locally, clone the repo:
   ```bash
   git clone https://github.com/cognis-digital/fpv-strike-drone.git && cd fpv-strike-drone
   ```
3. Serve the static files (it is a self-contained HTML5 + JS canvas/WebGL app):
   ```bash
   python -m http.server 8000
   ```
4. Open the sim and fly by browsing to <http://localhost:8000>.
5. Host your own copy — any static host works (the repo is GitHub Pages-ready via `index.html` + `.nojekyll`); push to a gh-pages-enabled repo, or drop `index.html` on any CDN/static bucket.

## About
FPV Strike Drone — first-person drone flight & strike sim. Built as a self-contained browser experience (HTML5 + JS canvas/WebGL). Part of the [Cognis Digital](https://cognis.digital) labs.

`mermaid
flowchart LR
  P[Player] --> B[Browser / GitHub Pages]
  B --> E[HTML5 + JS engine]
  E --> R[Render loop · input · audio]
`

## Run locally
```bash
git clone https://github.com/cognis-digital/fpv-strike-drone.git && cd fpv-strike-drone
python -m http.server 8000   # then open http://localhost:8000
```

## Interoperability

`fpv-strike-drone` composes with the 300+ tool Cognis suite — JSON in/out and a shared
OpenAI-compatible `/v1` backbone. See **[INTEROP.md](INTEROP.md)** for the
suite map, composition patterns, and reference stacks.

## Integrations

Forward `fpv-strike-drone`'s findings to STIX/MISP/Sigma/Splunk/Elastic/Slack/webhooks via
[`cognis-connect`](https://github.com/cognis-digital/cognis-connect). See **[INTEGRATIONS.md](INTEGRATIONS.md)**.

## License
COCL v1.0 — see [LICENSE](LICENSE).
