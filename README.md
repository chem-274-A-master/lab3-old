# CHEM 274A - Lab 3
September 27, 2022

Today, we will be focusing on Quantum Mechanics Tools using Python, matplotlib, numpy, and the `psi4` library.

## Objectives
- Analyze and optimize the geometry of a molecule using PsiAPI
- Plot bond length and energy changes during an optimization
- Define dihedral angles for intramolecular coordinates
- Use loops
- Scan and plot 2D and 3D models of potential energy surfaces (PES) for the interaction between two molecules

## Setup
1. Clone this repo!
2. Create a `conda` environment.
  a. Open a Terminal on Mac/Linux or Anaconda Prompt on Windows.
  b. Type the following prompt and hit Enter.

### Windows command
```
conda install -c raimis -c psi4 -c conda-forge psi4=1.3.2
```

### Mac/Linux command
```
conda install psi4 psi4-rt python=3.7 -c psi4
```

3. This will install PsiAPI in an environment called `qm-tools`.

## Exercise
Use the notebook `qm_lab3_geometry_optimization.ipynb` to explore Geometry Optimization. Follow the instructions in the notebook.
Use the notebook `qm_lab3_intramolecular.ipynb` to explore Intramolecular Potential Energy Surfaces. Follow the instructions in the notebook.
Use the notebook `qm_lab3_intermolecular.ipynb` to explore Intermolecular Potential Energy Surfaces. Follow the instructions in the notebook.