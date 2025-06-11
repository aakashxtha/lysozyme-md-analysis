# Lysozyme Molecular Dynamics Simulation

A complete workflow for running molecular dynamics simulations on lysozyme protein using GROMACS.

## Overview

This notebook performs:
- Protein preparation and solvation
- 10ns molecular dynamics simulation
- Pocket detection and analysis
- 3D visualization and data analysis

## Requirements

```
numpy
matplotlib
py3Dmol
fpocket
GROMACS (installed via conda)
```

## What it does

1. **Preparation**: Clean protein structure and add water box
2. **Simulation**: Run 10ns MD simulation in GROMACS
3. **Analysis**: Calculate RMSD, RMSF, and detect binding pockets
4. **Visualization**: 3D molecular viewer and interactive plots

## Usage

1. Run all cells in order
2. Results saved in respective folders

## Output

- Trajectory files (.xtc, .tpr)
- Analysis plots (RMSD, RMSF)
- Pocket detection results

