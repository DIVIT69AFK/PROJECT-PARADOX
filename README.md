# PROJECT PARADOX
### Generate · Explore · Compete

An interactive procedural 3D maze experience built with HTML, CSS, JavaScript and Three.js.

## Play
Once GitHub Pages is enabled, open:
https://divit69afk.github.io/PROJECT-PARADOX/

## Features
- Procedural maze generation using randomized Depth-First Search.
- Three maze complexity settings and adjustable odd dimensions.
- A guaranteed connected maze with a reachable key and exit.
- Keyboard movement, collision detection, restart and live run telemetry.
- Breadth-First Search (BFS) and A* pathfinding visualisations.
- Human vs Algorithm race mode.
- Responsive interface for desktop and mobile screens.

## Controls
- W / A / S / D or arrow keys: move
- R: restart the current run
- How to Play: in-app instructions

## Algorithms
**Maze generation:** randomized Depth-First Search carves a connected maze by visiting unvisited cells two steps away and opening the intervening wall.

**BFS:** explores the unweighted maze level by level and returns a shortest route.

**A*:** uses the Manhattan-distance heuristic to guide its search. With unit-cost grid movement and this admissible heuristic, it also returns a shortest route.

The solver's visited-cell count is displayed as a simple search-effort metric. It is not a benchmark of overall algorithm performance across different hardware.

## Run locally
No build step is required. Open `index.html` using a local web server (for example, VS Code Live Server). The Three.js module is loaded from jsDelivr, so an internet connection is needed.

## Publish with GitHub Pages
1. Open the repository's **Settings → Pages**.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select branch **main** and folder **/(root)**, then save.
4. Wait for the Pages deployment to finish. The public URL is shown in the Pages settings.

## Stack
- HTML5, CSS3 and JavaScript modules
- Three.js
- Randomized DFS, BFS and A*
- GitHub Pages

---
Built for the PROJECT PARADOX school subject expo.
