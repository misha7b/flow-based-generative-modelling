# Flow-Based Generative Modelling

## Overview

2D toy experiments comparing Flow Matching and Equilibrium Matching, plus supporting visualisations.

## Notebooks

| Notebook | Description |
|---|---|
| `flow_matching_2d.ipynb` | Flow Matching on 8 Gaussians, Two Moons, Checkerboard. ODE solver comparison (Euler, Midpoint, RK4). |
| `eqm_2d.ipynb` | Equilibrium Matching on the same datasets. Compares decay schedules and descent methods (GD, Heavy Ball, Nesterov, Langevin). |
| `probability_paths.ipynb` | Conditional vs marginal probability paths. |
| `vector_field_time_dependent.ipynb` | Vector field with ODE trajectories. |
| `plot.ipynb` | 1D probability path heatmap interpolating between a Gaussian and a mixture. |
| `toy_nn_example.ipynb` | Simple MLP fitting sin(x) from noisy data. |

## Requirements

```
torch numpy matplotlib scikit-learn tqdm POT scipy Pillow
```