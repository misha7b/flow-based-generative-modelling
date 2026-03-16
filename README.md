# Flow-Based Generative Modelling


## Overview

This repository contains 2D toy experiments comparing Flow Matching and Equilibrium Matching.

- `flow_matching_2d.ipynb` — Flow Matching on 8 Gaussians, Two Moons, and Checkerboard, including an ODE solver comparison (Euler, Midpoint, RK4).
- `eqm_2d.ipynb` — Equilibrium Matching on the same datasets, comparing decay schedules and descent methods.


## Requirements

```
torch
numpy
matplotlib
scikit-learn
tqdm
POT
```