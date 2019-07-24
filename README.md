# An jypter notebook based introduction to the particle-in-cell algorithm

## Purpose
The primary purpose of this repository is to provide an introduction to the rudimentary particle-in-cell algorithm. 
Examples are based on laser-plasma physics and standard plasma instabilities.


## Fundamental steps
The different steps of the particle-in-cell algorithm:
 - solving the time-dependent Maxwell equations to update the electromagnetic field
 - interpolating the field values onto the particles to compute the Colomb force 
 - solving the equation of motion based on the previously calculated force
- compute the current created by the particle motion and interpolate it onto the simulation grid
will be treated separately.

## Using jupyter
In order to provide an easy to use development environment, this project provides jupyter notebooks in python. 
This approach is inspired by the great work of @labarba et al. regarding, for example, the tutorial on the [Navier-Stokes equation](https://github.com/barbagroup/CFDPython). 

## Status
As of now, this is work in progress and far from complete. Feel free to contribute.  