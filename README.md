# CFD – Flow in a Stenosed Aorta

## Overview

Biomedical engineering computational fluid dynamics project investigating blood flow through a stenosed aorta using numerical simulation and flow analysis.

## Project Aim

The project aimed to model blood flow through an arterial stenosis and investigate how the narrowed geometry affects flow behaviour, including pressure, velocity and flow separation.

## My Work

I:

- Developed a computational model of blood flow through a stenosed aorta
- Created and refined the computational mesh to support reliable numerical results
- Applied appropriate numerical schemes and monitored solution convergence
- Investigated changes in velocity and pressure through the stenotic region
- Analysed flow behaviour downstream of the stenosis, including regions of disturbed flow and flow separation
- Interpreted the simulation results in the context of cardiovascular haemodynamics
## Project Visuals

### Stenosed Aorta Geometry

Simplified aortic geometry used for the CFD model, including the stenotic region.

![Stenosed aorta geometry](https://raw.githubusercontent.com/yemesis/cfd-stenosed-aorta/main/figures/stenosed-aorta-geometry.png)

### Second-Order Flow Separation

X-position versus Y-velocity results from the second-order simulations, showing negative velocity and post-stenotic backflow associated with flow separation.

![Second-order flow separation](https://raw.githubusercontent.com/yemesis/cfd-stenosed-aorta/main/figures/second-order-flow-separation.png)

### First- vs Second-Order Flow Separation

Comparison of flow-separation behaviour between first- and second-order numerical solutions, demonstrating the effect of discretisation accuracy on the predicted backflow.

![First vs second order flow separation](https://raw.githubusercontent.com/yemesis/cfd-stenosed-aorta/main/figures/first-vs-second-order-flow-separation.png)
## Key Findings

The simulations showed that mesh refinement and second-order discretisation improved the resolution of complex flow behaviour around and downstream of the stenosis.

The second-order solutions produced higher resolved backflow velocities, reaching approximately **-0.20 m/s**, compared with approximately **-0.18 m/s** for the first-order solutions. The report identified the **second-order fine mesh** as the most accurate configuration for resolving velocity gradients, pressure transitions and post-stenotic flow separation.

The analysis also showed that first-order schemes were more affected by artificial viscosity, while finer meshes captured separation points and vortices more clearly.

## Methods

- Computational Fluid Dynamics
- Numerical modelling
- Mesh generation and refinement
- Convergence analysis
- Pressure analysis
- Velocity analysis
- Flow separation analysis
- Haemodynamic interpretation

## Tools

- STAR-CCM+
- Computational mesh generation
- Numerical simulation

## Skills Demonstrated

- CFD modelling
- Numerical analysis
- Biomedical fluid mechanics
- Data interpretation
- Engineering problem solving
- Simulation and model evaluation
- Technical reporting

## Project Materials

- [View Project Report](./cfd-stenosed-aorta-report.pdf)
