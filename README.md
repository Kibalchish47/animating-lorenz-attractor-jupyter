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
One normally assumes that the parameters σ, ρ, and β are positive. Lorenz used the values $\sigma = 10, \beta = 8/3$ and $\rho = 28$. The system exhibits chaotic behavior for these (and nearby) values.

If $\rho < 1$ then there is only one equilibrium point, which is at the origin. This point corresponds to no convection. All orbits converge to the origin, which is a global attractor, when $\rho < 1$.

A pitchfork bifurcation occurs at ρ = 1, and for ρ > 1 two additional critical points appear at: 
$(\sqrt{\beta(\rho - 1)}, \sqrt{\beta(\rho - 1)}, \rho - 1)$ and $(-\sqrt{\beta(\rho - 1)}, -\sqrt{\beta(\rho - 1)}, \rho - 1)$. 

These correspond to steady convection. This pair of equilibrium points is stable only if
$$
\rho <\sigma {\frac {\sigma +\beta +3}{\sigma -\beta -1}},
$$,
which can hold only for positive ρ if $\sigma > \beta + 1$. At the critical value, both equilibrium points lose stability through a subcritical Hopf bifurcation.

When ρ = 28, σ = 10, and β = 8/3, the Lorenz system has chaotic solutions (but not all solutions are chaotic). Almost all initial points will tend to an invariant set – the Lorenz attractor – a strange attractor, a fractal, and a self-excited attractor with respect to all three equilibria. 

Its Hausdorff dimension is estimated from above by the Lyapunov dimension (Kaplan-Yorke dimension) as 2.06±0.01, and the correlation dimension is estimated to be $2.05±0.01$. The exact Lyapunov dimension formula of the global attractor can be found analytically under classical restrictions on the parameters:

$ \displaystyle 3-{\frac {2(\sigma + \beta +1)}{\sigma + 1 +{\sqrt {\left(\sigma -1\right)^{2} + 4\sigma \rho }}}} $

The Lorenz attractor is difficult to analyze, but the action of the differential equation on the attractor is described by a fairly simple geometric model. Proving that this is indeed the case is the fourteenth problem on the list of Smale's problems. This problem was the first one to be resolved, by Warwick Tucker in 2002.

For other values of $\rho$, the system displays knotted periodic orbits. For example, with $\rho = 99.96$ it becomes a $T(3,2)$ torus knot.