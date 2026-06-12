# HiveHue

**Retro-Futurist Scientific Illustration** by Leonel Palacios.

Live site: **[hivehue.art](https://hivehue.art)**

HiveHue is a portfolio of scientific illustrations where the geometry, the
trajectories, and the physics are actually correct. Each piece is drawn from
real physics and primary sources — orbital mechanics, relativity, plasma
physics, and spaceflight — in the visual language of 1930s–60s science posters:
Bauhaus structure, WPA boldness, and Space-Race optimism, with a deliberate 3–5
colour palette and bold typography.

## About the work

The illustrations are made by someone who has worked on the subjects they
depict — a background spanning industrial design, engineering physics, a PhD in
aerospace engineering, and a decade in spacecraft guidance, navigation, and
control. The result is figures that are both editorially striking and
technically right, intended for editors, researchers, and grant reviewers.

A few examples from the gallery:

- **Tokamak** — fusion drawn as a system of symbols, encoding the etymology of
  deuterium and tritium in the strand counts.
- **The Three-Body Problem** — trajectories numerically integrated in Python,
  showing what deterministic chaos actually looks like.
- **Starshade** — a NASA external occulter, with petal geometry derived from
  apodization theory.
- **Penrose Diagram** — the maximally extended Schwarzschild solution, light
  rays at exactly 45°.
- **Hohmann Transfer** — Walter Hohmann's 1925 propellant-minimizing two-burn
  transfer.

## Structure

This is a static site — plain HTML and CSS, no build step.

| Path | Description |
| --- | --- |
| `index.html` | Main portfolio page: gallery, about/method, experiments, contact. |
| `perspective.html` | **Perspective Lab** — an interactive study in depth, an experiment exploring how an image works rather than what it depicts. |
| `images/` | Illustration files and Open Graph thumbnails. |
| `CNAME` | Custom domain (`hivehue.art`) for GitHub Pages. |

The gallery content lives in the `WORKS` array near the bottom of
`index.html` — each entry has an image path, title, kicker, description, and
metadata, and drives both the grid and the lightbox.

## Running locally

No dependencies or build step. Open `index.html` directly, or serve the folder:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deployment

Hosted on GitHub Pages with the custom domain in `CNAME`. Pushes to the default
branch publish automatically. The site uses GoatCounter for anonymous,
cookie-free visitor statistics.

## Contact

[designer@hivehue.art](mailto:designer@hivehue.art)

© 2026 Leonel Palacios — HiveHue. All rights reserved.
