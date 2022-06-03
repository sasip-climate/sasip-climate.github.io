---
title: ' Code'
heroHeading: 'Code'
heroSubHeading: 'Public repository and data access'
heroBackground: '/images/photo-1542831371-29b0f74f9713.jpeg'
---

#### Codes

Our codes are hosted on our Github [repository](https://github.com/m2lines). 

- Code for subgrid ML parameterizations: 
  * [Atmospheric Momentum Parametrization](https://doi.org/10.5281/zenodo.5083483) (Yuval and O'Gorman 2021): Neural Network Parameterization of subgrid momentum using SAM data
  * [Ocean Momentum Parameterization](https://doi.org/10.5281/zenodo.5076046) (Guillaumin and Zanna 2021): Convolutional Neural Network subgrid momentum using CM2.6 data 
 
- Implementation of ML parameterizations & numerical solvers: 
  * [Stochastic Deep Learning Parameterization](https://doi.org/10.5281/zenodo.4573448): Online implementation of Guillaumin & Zanna in an idealized barotropic model
  * [TorchQG](https://github.com/hrkz/torchqg): Differentiable quasi-geostrophic spectral solver in PyTorch with ML parameterizations
  * [Parameterizations in pyqg](https://github.com/pyqg/pyqg) : e.g., implementation of Zanna & Bolton 2020 
  * [MOM6 Implementation of data-driven parameterization](https://github.com/Pperezhogin/MOM6/blob/Zanna-Bolton-2020/src/parameterizations/lateral/MOM_Zanna_Bolton.F90): e.g., Zanna & Bolton 2020. 

- Software Package
  * [GCM-filter](https://github.com/ocean-eddy-cpt/gcm-filters) : software package filtering ocean model data, including in the presence of topography. 


Upcoming codes will be linked to this repository as they become available.

#### Datasets

All of the datasets used in M²LInES publications will be made openly available. When possible, they will be hosted on [Pangeo](https://pangeo.io/)

