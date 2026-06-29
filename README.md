<div align="center">

# PIC Projects: RF Ion Thruster Plasma Simulations

![Plasma Physics](https://img.shields.io/badge/Plasma%20Physics-1a1a2e?style=for-the-badge)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![OpenFOAM](https://img.shields.io/badge/OpenFOAM-0057B8?style=for-the-badge)
![PIC Method](https://img.shields.io/badge/Particle--in--Cell-2d6a4f?style=for-the-badge)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

</div>

## Overview

This repository contains a collection of Particle-in-Cell (PIC) plasma
simulations, hardcoded from first principles in Python, developed to study
the fundamental wave and kinetic phenomena that govern plasma behaviour in
RF Ion Thrusters. The simulations follow the standard electrostatic (ES1)
and electromagnetic (EM1) PIC frameworks, and progress from basic
single-particle dynamics to more involved collective plasma phenomena such
as plasma oscillations, wave propagation, and Landau damping.

## What's Inside

The repository is organized around individual plasma phenomena, with each
simulation built up from a shared foundation of grid setup, particle
initialization, and the core PIC computational cycle. Notebooks are
accompanied by their corresponding output visualizations to aid in
interpreting particle and field behaviour over time.

## Tech Stack

- **Python** : core language used for all hardcoded PIC simulations
- **Jupyter Notebooks** : primary environment for development and
  visualization
- **OpenFOAM** : explored as a framework for more advanced,
  mesh-based plasma simulation
- **NumPy / Matplotlib** : used
  for numerical computation and visualization

## Background

These simulations were developed as part of an internship on RF Ion
Thrusters at the Applied Plasma and Space Propulsion Laboratory, Department
of Aerospace Engineering, IIT Madras, to build a computational
understanding of the plasma physics underlying RF-coupled discharge
sustenance.
