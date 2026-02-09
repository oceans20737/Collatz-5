
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.18525450.svg)](https://doi.org/10.5281/zenodo.18525450)

Title: Collatz‑5 Python Implementation
Author: Hiroshi Harada
Year: 2026
License: CC BY 4.0

Description
This archive provides a minimal and clean Python implementation of the Collatz‑5 dynamical system, also known as the Pentadica map.
The Collatz‑5 map is defined by modular rules based on n mod 5, consisting of four Outer‑Circuit update rules and a division rule when n is divisible by 5.
The system always converges to the stable core {1, 2, 3}, but many numbers exhibit glider‑like behavior, remaining in the Outer Circuit (mod 5 = 1, 2, 3, 4) for long periods before eventually falling into deeper layers.
This code supports numerical exploration of such behavior, including long gliders, high‑altitude jumpers, and legendary escape‑like trajectories.

Included Functions
- collatz5_step(n): one iteration of the 5‑adic map
- collatz5_orbit(n): orbit generation until reaching {1, 2, 3}
- OrbitStats: steps, laps, maximum value, classification
- is_P32(n): simple P(3,2) filter (numbers not divisible by 2, 3, or 5)
- demo_single(n): print orbit and statistics for one number
- demo_range(a, b): scan a range for glider‑like behavior

Files in this archive
- collatz5.py (main implementation)
- README.md (GitHub‑style documentation)
- LICENSE (CC BY 4.0)

Purpose
This archive is intended for reproducible research, numerical experiments, and exploration of glider‑like and escape‑like behavior in the Collatz‑5 system.
It provides a compact reference implementation suitable for:
- orbit visualization
- classification of racer types
- P(3,2) sequence exploration
- detection of long Outer‑Circuit runs
- identification of high‑altitude or legendary gliders

Citation
If you use this code, please cite the Zenodo DOI associated with this archive.

Contact
Hiroshi Harada



