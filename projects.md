# Project description

These are the two projects for the group development stage. Please adhere to the general and individual requirements for your project.

## General requirements

- develop your project on Github
- provide your code as a Python package
- provide an automated unit test suite with your package
- provide a documentation of your package
- ensure compatibility with Python-2.7 and Python-3.5
- only third party packages available via conda and the Python package index are allowed as dependencies
- third party code for MD, MC, PME, or Ewald summation may not be used
- use suitable approaches like cython or numba to provide fast code
- every group member must actively contribute to the development process

## Project I: MC

Design and implement a Python package to perform Metropolis Monte Carlo and simulated tempering simulations of non-bonded point particles in a three dimensional, orthorombic, $x$-/$y$-/$z$-periodic cell. Use a suitable cutoff scheme and the Ewald summation or particle mesh Ewald technique to compute the electrostatic interaction (Coulomb + Lennard-Jones).

## Project II: MD

Design and implement a Python package to perform molecular dynamics and steepest descent simulations of non-bonded point particles in a three dimensional, orthorombic, $x$-/$y$-/$z$-periodic cell. Use a suitable cutoff scheme and the Ewald summation technique to compute the electrostatic interaction (Coulomb + Lennard-Jones).

