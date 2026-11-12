# Same Stage, Different Profiles

Supporting material for the poster *Same Stage, Different Profiles: Do full-time high schools in Brazil have lower failure and dropout rates?* (English 2 Poster Fair, IMPA Tech, 2026).

**Authors:** Ryan Kevin and Yasmin de Barros · **Advisor:** Prof. Nara Bobko

**References page:** https://ry4n-felinto.github.io/english2_poster_references/

## Contents

| Path | What it is |
|---|---|
| `data/` | Dataset used in the analysis (`bd8.zip`, school-level data from INEP, 2011–2025) and its data dictionary |
| `graficos_poster_final.ipynb` | Notebook that reproduces all figures and tables |
| `images/` | The four poster figures (PNG and SVG) |
| `tables/` | Summary tables behind the figures and the numbers in the poster |
| `index.html` | References page |

## How to reproduce

Requires Python 3 with `pandas`, `numpy` and `matplotlib`. Open `graficos_poster_final.ipynb` and run all cells. The notebook reads `data/bd8.zip` directly (no need to unzip) and writes the figures to `images/` and the tables to `tables/`.
