# Volumes by Integration — Visual Guide

An interactive, single-file web app that helps students *see* what happens during
volume integration. Drag to orbit, scroll to zoom, and watch Riemann sums sharpen
into exact integrals.

🔗 **Live demo:** https://eunnip.github.io/volume-integration/

## What's inside

Each tab follows the same teaching arc — **goal → what happens → how to calculate**:

- **Intuition** — spin a curve into a 3-D solid of revolution.
- **Disk method** — slice into coins; a slider grows the number of disks and shows
  the sum approaching the exact integral, with a live error bar.
- **Washer method** — disks with holes (rotating the region between two curves).
- **Shell method** — nested cylindrical shells for rotation about the y-axis.
- **Cross-sections** — stacked squares, semicircles, or triangles (no rotation).
- **Triple integral** — towers under a surface, extending the idea to 3-D.
- **Calculator** — type any function (`x^3`, `sin(x)+1`, `e^(-x)`, `1/(x+1)`, …),
  set the limits, pick a method, and see the solid and exact volume computed live.

## Running it

It's a single self-contained HTML file — just open `index.html` in any modern
browser. The only external dependencies are Three.js and MathJax, loaded from a CDN.

## Tech

Plain HTML/CSS/JS, [Three.js](https://threejs.org/) for the 3-D views, and
[MathJax](https://www.mathjax.org/) for the formulas. No build step.

## License

MIT — see [LICENSE](LICENSE).
