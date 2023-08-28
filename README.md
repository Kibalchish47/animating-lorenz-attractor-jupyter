# Animating-Lorenz-Attractor
Lorenz system animation and visualization of its strange attractor with Python (Jupyter Notebook). 
This project is based on the code provided in this article: https://geoffboeing.com/2016/12/animating-lorenz-attractor-python/.

Table of Contents: 
- 
## Introduction
Edward Lorenz, the father of chaos theory, once described chaos as "[...] when the present determines the future, but the approximate present does not approximately determine the future". 

Lorenz first discovered chaos by accident while developing a simple mathematical model of atmospheric convection, using three ordinary differential equations. He found that nearly indistinguishable initial conditions could produce completely divergent outcomes, rendering weather prediction impossible beyond a time horizon of about a fortnight (14 days).

In 1963, Lorenz developed this simple model (consisting of a system of 3 ordinary differential equations) of the way air moves around in the atmosphere:

$$
\frac{{dx}}{{dt}} = \sigma(y - x)
$$
$$
\frac{{dy}}{{dt}} = x(\rho - z) - y
$$
$$
\frac{{dz}}{{dt}} = xy - \beta z
$$

Now known as the Lorenz System, this model demonstrates chaos at certain parameter values, and its attractor is fractal (the trajectories never overlap).

The equations relate the properties of a two-dimensional fluid layer uniformly warmed from below and cooled from above. In particular, the equations describe the rate of change of three quantities with respect to time: x is proportional to the rate of convection, y to the horizontal temperature variation, and z to the vertical temperature variation. The constants σ, ρ, and β are system parameters proportional to the Prandtl number, Rayleigh number, and certain physical dimensions of the layer itself.

The Lorenz equations can arise in simplified models for lasers, dynamos, thermosyphons, brushless DC motors, electric circuits, chemical reactions, and forward osmosis. The Lorenz equations are also the governing equations in Fourier space for the Malkus waterwheel.

From a technical standpoint, the Lorenz system is nonlinear, aperiodic, three-dimensional and deterministic. The Lorenz equations have been the subject of hundreds of research articles, and at least one book-length study.

## The Project

## Analysis of the Lorentz System
