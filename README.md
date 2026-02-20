# ME5311 Project 1 — Spatio-temporal Data Analysis (Python)
Data-Driven Engineering  and Machine Learning

This repository contains my code for **ME5311 Project 1** (Data analysis only).  
The goal is to explore the provided spatio-temporal dataset using data-driven analysis tools (e.g., SVD/modal decomposition, spectral/Fourier analysis, statistical characterization).

> ⚠️ **Project 1 constraint:** Modelling system dynamics or performing prediction tasks is **NOT** allowed for Project 1.

---

## Dataset

- Type: time-resolved snapshots of a **two-component vector field** on a 2D periodic square domain.
- Grid: **64 × 64**, two components per grid point.
- Time: `nt = 15000` snapshots, sampled with `Δt = 0.2` (simulation units).
- File: `vector_64.npy` (or `vector_64.mat`).

### Download link
Copy the dataset into `data/raw/`:

```text
https://nusu-my.sharepoint.com/:f:/g/personal/e1500557_u_nus_edu/IgBD9b1ASir8Q5bwz7O3XYewAa-ox6PVUEoWV0TZ0xsjSCM
