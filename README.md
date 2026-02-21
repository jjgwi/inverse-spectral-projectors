# inverse-spectral-projectors

Companion code for the paper **“[TITLE OF PAPER]”** (arXiv: [XXXX.XXXXX]).

This repository contains a reference implementation of the synthetic benchmark used in the paper:
a spectral forward model (mode-sum for the thermal free energy) and a regression-stencil projector that compresses a
finite scan window into a robust scalar statistic for inference.

## Contents

- `inverse-spectral-projectors.ipynb` — main notebook (forward model, projection/stencil, inference, and figure generation): available here
- `data/geometry_library.npz` — precomputed spectrum library used by the notebook: is generated
- `geometry_engine.py` — spectrum generation (Sturm–Liouville / tridiagonal eigenproblem): is generated
- `fig_*.pdf` — output figures: are regenerated