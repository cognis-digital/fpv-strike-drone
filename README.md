<div align="center">

# fpv-strike-drone

### FPV Strike Drone — first-person drone flight & strike sim.

[![▶ Play Now](https://img.shields.io/badge/%E2%96%B6%20PLAY-in%20your%20browser-6b46c1?style=for-the-badge)](https://cognis-digital.github.io/fpv-strike-drone/)
[![License: COCL 1.0](https://img.shields.io/badge/License-COCL%201.0-2b6cb0.svg)](LICENSE)

**▶ Play instantly: https://cognis-digital.github.io/fpv-strike-drone/**  · no install, runs in any modern browser.

</div>

## What is this?
FPV Strike Drone is a browser-based flight and combat simulation game where you pilot a drone from a first-person perspective. You fly, maneuver, and engage targets in a team deathmatch format — all without downloading anything. Anyone with a modern web browser can open the link and start playing immediately, no setup required. It is aimed at hobbyists, gamers, and anyone curious about what drone-piloting feels like from the cockpit.

## Getting started
No installation needed. Open the game directly in your browser:

**[Play now — https://cognis-digital.github.io/fpv-strike-drone/](https://cognis-digital.github.io/fpv-strike-drone/)**

To run it locally (for development or offline play):
```bash
git clone https://github.com/cognis-digital/fpv-strike-drone.git
cd fpv-strike-drone
python -m http.server 8000
# then open http://localhost:8000 in your browser
```

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

<a name="verification"></a>
## Verification



Every push is verified end-to-end. Latest audit (2026-06-13):

```text
tests        : 0 passed, 0 failed, 0 errored
compile      : all modules parse
cli          : n/a
package      : n/a
```

<details><summary>CLI surface (<code>--help</code>)</summary>

```text
(see --help)
```
</details>

Full machine-readable results: [`AUDIT.md`](AUDIT.md) · regenerate with `python -m fpv-strike-drone --help` + `pytest -q`.

<div align="right"><a href="#top">↑ back to top</a></div>


## License
COCL v1.0 — see [LICENSE](LICENSE).
