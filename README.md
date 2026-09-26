# Numerical Solution of the Laplace Equation

A Python-based numerical study of electrostatic potential and electric-field distributions by solving the two-dimensional Laplace equation using the finite-difference method.

## Overview

This project investigates the numerical solution of the Laplace equation for different two-dimensional geometries and boundary conditions.

The simulations include:

- Finite-difference solution of the Laplace equation
- Electric potential distribution
- Electric-field calculation from the potential gradient
- 3D visualization of potential
- Convergence toward equilibrium
- Computational time as a function of mesh size
- Potential evolution during the iterative solution
- Visualization of different boundary-condition configurations
- Potential-distribution animation

## Main Method

The Laplace equation is solved iteratively using the finite-difference approximation.

At each iteration, the potential at an interior grid point is updated from the neighboring grid points until the maximum change between successive iterations falls below a specified tolerance.

The electric field is then obtained from the numerical gradient of the potential.

## Configurations

### 1. Non-Uniform / L-Shaped Configuration

The first configuration models a square computational domain containing a region with a fixed potential and surrounding boundary conditions.

The simulation produces:

- Potential contour maps
- Electric-field vector plots
- 3D potential distributions
- Potential evolution toward equilibrium
- Computational time versus mesh size
- Visualization of the simulated geometry

### 2. Square-Domain Verification

Additional configurations were implemented to verify the numerical solver under simpler boundary conditions.

These cases include:

- A square domain with specified potentials on selected boundaries
- A configuration with a single non-zero boundary
- Comparison of potential and electric-field distributions
- Mesh-size and convergence analysis

These verification cases provide simpler geometries for checking the behavior of the numerical solution.

## Visualizations

The project generates several types of plots:

- 2D potential contour maps
- Electric-field vector (quiver) plots
- 3D potential surfaces
- Potential versus iteration
- Computational time versus mesh size
- Domain and boundary-condition visualization
- Animated potential evolution

## Technologies

- Python
- NumPy
- Matplotlib
- Matplotlib 3D
- Pillow
