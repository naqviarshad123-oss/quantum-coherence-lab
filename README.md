# Quantum Coherence Lab

This repository documents an experimental and analytical study of quantum coherence
using Ramsey, Hahn Echo, and CPMG pulse sequences on IBM Quantum hardware.

## Overview

The goal of this project is to understand:
- Phase evolution and dephasing (Ramsey experiment)
- Noise refocusing via spin echo (Hahn Echo)
- Noise spectral filtering using multi-pulse dynamical decoupling (CPMG)

All experiments are implemented using Qiskit and executed on IBM Quantum backends.

## Key Results (Initial)

- Ramsey dephasing time: **T2\*** ≈ 2–3 µs  
- Hahn Echo coherence time: **T2** ≈ 35–40 µs  
- CPMG scaling exponent: α ≈ −0.1 (indicative of low-frequency noise dominance)

## Methods

- Time delays implemented in backend `dt` units
- Expectation values ⟨Z⟩ extracted from measurement counts
- Exponential decay fits applied in carefully selected time windows
- Analysis performed in Python using NumPy and Matplotlib

## Repository Structure (planned)

```text
quantum-coherence-lab/
├── notebooks/
│   ├── ramsey.ipynb        # Ramsey experiment and T2* extraction
│   ├── hahn_echo.ipynb     # Hahn echo coherence measurement
│   └── cpmg.ipynb          # CPMG pulse sequence analysis
├── analysis/
│   ├── decay_fits.py       # Exponential and envelope fitting
│   └── noise_models.py    # 1/f vs white noise models
├── figures/
│   └── ramsey_decay.png
├── README.md

This project is intended as:
- A learning lab for quantum coherence and noise
- A portfolio-quality research artifact
- Preparation for graduate study or research roles in quantum science

## Status

Active development.
