# PIC 
This repository contains a particle in cell simulation of an Ar/CF4 plasma in a 2D Grid with a magnetic field coming out of the x-y plane (and with a potential set on the upper first row of the grid) through the boris push method for the module Computational Physics I. The tasks to be done are the following:

- Setup the 2D Grid
  1. Create the spatial structure
  2. Set the boundary conditions of the grid. In this case the x dimension is periodic, while the y direction is not. If a particle hits the y[0] or y[N] cell, then it is absorbed.
  3. Add magnetic and electric field properties to each cell (to find E, a Poisson Solver must be defined). These field must be constant along time.
    
- Initialize particles:
  1. Define the distribution of the particles at the beginning of the simulation and their current.
  2. Set the parameters of each particle (velocity, position, charge, mass, etc.)

- Implement Boris Push:
  1. Use the Boris (Leap-Frog) algorithm to update particle velocities and positions.
  2. Ensure stability region by choosing an appropriate delta t
 
- Diagnostics:
  1. Compute and save data (e.g. density, energy, temperature etc.)
  2. Compare the results with papers.
 
- Problem solving:
  1. Look up for inconsistencies in the model and find a proper solution (if available) and/or explanation for them.
  MIlestones for the project:
  
