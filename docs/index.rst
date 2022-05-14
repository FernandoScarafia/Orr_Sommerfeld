 Welcome to  Orr Sommerfeld documentation!
 =========================
It is a python package developed in order to solve the Orr Sommerfeld equations. It is free for the community and allows to calculate disturbances for 4 flows of interest: Poiseuille, Couette, Boundary Layer and jet. These perturbations can be used to analyze the phenomenon of the laminar-turbulent transition. 
 
## Table of contents
* [General info](#general-info)
* [Technologies](#technologies)
* [Installation](#installation)
* [Examples](#examples)

## General info

Fluid systems are often described and characterized by their stability or receptivity behavior. Perturbations of infinitesimal amplitude that grow when superimposed on an equilibrium state of the flow render the base flow unstable.

The Orr–Sommerfeld equation, is an eigenvalue equation describing the linear two-dimensional or three-dimensional modes of disturbance to a viscous parallel flow. The solution to the Navier–Stokes equations for a parallel, laminar flow can become unstable if certain conditions on the flow are satisfied, and the Orr–Sommerfeld equation determines precisely what the conditions for hydrodynamic stability are.

## Technologies
Project is created with:
* [NumPy](https://numpy.org/)
* [SciPy](https://scipy.org/)
* [PyPi](https://pypi.org/) to publish Python package.


## Installation
It is possible to install using pip:
```Python
pip install Orr_Sommerfield
```
## Examples
* Importing the package:
```Python3.9
from Orr_Sommerfeld import OS
```
* Can compute the spectrum of temporal and spatial eigenvalues and their respective perturbations using:
```Python
lam,u,v,w=OS.Orr_Sommerfeld_Temporal(N,R,alp,b,n,Np)
```
* For temporal problem and 
```Python
lam,u,v,w=OS.Orr_Sommerfeld_Espacial(N,R,w,b,n,Np)
```
* For spacial problem.
Finally, The idea is that it is used in "Jupyter Notebook" to facilitate its processing.
