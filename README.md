# RocketPy
[![Run Changed Jupyter Notebooks](https://github.com/ULAS-HiPR/RocketPy/actions/workflows/run-ipynbs-onchange.yaml/badge.svg?branch=main)](https://github.com/ULAS-HiPR/RocketPy/actions/workflows/run-ipynbs-onchange.yaml)
Flight simulation utilities, notebooks, and experiments in High Powered Rocketry.

## Projects
- [Mach24](./Mach24/README.md): A 3D simulation of the Mach 24 rocket Morrigu's flight.
- [EuRoC24](./EuRoC24/README.md): A 3D simulation of the EuRoC rocket's flight.

## Installation

```bash
# Setup environment
conda env create -f environment.yml

# Activate environment
conda activate rocketpy_env

# If you add a dependency do this 
conda env export > environment.yml
```