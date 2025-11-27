# laplace-rectangular-waveguide
Analytical solution of Laplace's equation for electrostatic potential in rectangular geometry
# Laplace Equation Solution for Rectangular Metallic Tube

## Problem Description
Analytical solution of the electrostatic potential inside an infinite rectangular metallic tube using separation of variables and Fourier series.

**Physical System**: Two infinitely long metallic plates at y=0 and y=a, connected by metallic strips at x=±b maintained at constant potential V₀.

## Mathematical Solution
The potential V(x,y) satisfies Laplace's equation:
∇²V = 0

With boundary conditions:
- V(x, 0) = 0
- V(x, a) = 0
- V(±b, y) = V₀

The analytical solution is:
V(x,y) = Σₙ [4V₀/((2n+1)π cosh((2n+1)πb/a))] × sin((2n+1)πy/a) × cosh((2n+1)πx/a)

## Features
- 3D visualization of electrostatic potential
- Interactive parameter input
- Fourier series implementation
- Professional scientific plotting

## Technologies Used
- Python 3
- NumPy - Numerical computations
- Matplotlib - 3D visualization
- mpl_toolkits - 3D plotting

## Results
The code generates:
- 3D wireframe plots of potential distribution
- Interactive parameter customization
- High-precision Fourier series solution

## Author
**I.I. D. Cortés** - ileonc001@alumno.uaemex.mx  
**Universidad Autónoma del Estado de México**

## Quick Start
```bash
pip install numpy matplotlib
python Laplace_solution.py
