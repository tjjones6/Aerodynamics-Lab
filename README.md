# Multi-Reynolds Number Aerodynamic Coefficient Analysis

This repository provides a Python-based aerodynamic post-processing tool to analyze wind tunnel data across multiple Reynolds numbers. It is tailored for experiments involving airfoils of varying aspect ratios (AR1, AR2, AR3) and includes corrections for the gravitational offset measured with the wind tunnel off.

## Features

- Computes lift and drag coefficients from raw balance data
- Corrects measured normal and axial forces using pre-collected zero-wind (off) data
- Groups and averages data by angle of attack (AoA)
- Computes Reynolds numbers automatically from velocity and chord
- Generates plots:
  - Lift coefficient (CL) vs. AoA
  - Drag coefficient (CD) vs. AoA
  - Drag polar (CL vs. CD)
  - Reynolds number effect on drag
- Supports batch processing of multiple CSV files
- Saves processed results and plots to a user-defined directory

## Getting Started

### Dependencies

- Python 3.7+
- numpy
- pandas
- matplotlib

Install dependencies with:

```bash
pip install -r requirements.txt
