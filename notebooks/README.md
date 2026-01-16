# Experiment Notebooks

This directory contains Jupyter notebooks implementing and analyzing
quantum coherence experiments on IBM Quantum hardware.

## Contents

- **ramsey.ipynb**  
  Ramsey experiment to study phase evolution and extract the dephasing time T2*.

- **hahn_echo.ipynb**  
  Hahn echo experiment demonstrating refocusing of low-frequency noise
  and extraction of coherence time T2.

- **cpmg.ipynb**  
  CPMG pulse sequence for noise spectral filtering and dynamical decoupling analysis.

Each notebook includes:
- Circuit construction using Qiskit
- Time delays implemented in backend `dt` units
- Measurement-based extraction of ⟨Z⟩
- Data visualization and decay fitting
