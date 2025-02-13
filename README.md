# Diffusion2D-Python-Package

## Instructions for students

Please follow the instructions in [exercise_python_packaging_text.md](https://github.com/Simulation-Software-Engineering/Lecture-Material/blob/main/building-and-packaging/material/exercise_python_packaging_text.md).

## Project description

This project's code numerically solves the two-dimensional diffusion equation on a squared domain. The domain has a certain temperature while the circular surface in the middle of the domain has a much higher temperature. The Finite Difference method is applied in order to obtain the solution to this diffusive problem. Certain parameters, i.e. initial conditions and thermal diffusivity, can be changed by the user. The results of this simulation are depicted in four plots at different timesteps.

## Installing the package

### Using pip3 to install from PyPI

In the terminal use

```pip3 install brenchladiffusion2D```

to install the package. 

### Required dependencies

- Python >= 3.6
- numpy
- matplotlib

## Running this package

A minimalistic example to run the code:

```python
from brenchladiffusion2D import diffusion2d
diffusion2d.solve()
```

## Citing

The code used in this exercise is based on [Chapter 7 of the book "Learning Scientific Programming with Python"](https://scipython.com/book/chapter-7-matplotlib/examples/the-two-dimensional-diffusion-equation/).

The solution at hand of this particular exercise is provided by Larissa Brencher (username brenchla on GitLab).
