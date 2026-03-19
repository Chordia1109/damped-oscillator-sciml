# Comparing Numerical Solvers and Physics-Informed Neural Networks for the Damped Harmonic Oscillator

## Project Overview
This project studies the damped harmonic oscillator and compares classical numerical solvers with a simple physics-informed neural network (PINN).

## Goals
- Model the damped harmonic oscillator
- Solve it using classical numerical methods
- Implement a simple PINN
- Compare accuracy, stability, and behavior of the methods

## Methods
- Reference/baseline solution
- Euler method
- Runge-Kutta 4 (RK4)
- Physics-Informed Neural Network (PINN)

## Repository Structure

- `notebooks/`: Jupyter notebooks for experiments
  - `01_baseline_solution.ipynb`
  - `02_euler_rk4.ipynb`
  - `03_pinn.ipynb`
- `figures/`: plots for the report and presentation
- `report/`: LaTeX report and final PDF
- `slides/`: presentation materials
- `src/`: reusable Python code for future extensions
## Status
## Problem Setup
The damped harmonic oscillator is governed by:

m x'' + c x' + k x = 0

with parameters:
- m = 1.0
- c = 0.4
- k = 4.0

initial conditions:
- x(0) = 1.0
- x'(0) = 0.0

time interval:
- t in [0, 10]
