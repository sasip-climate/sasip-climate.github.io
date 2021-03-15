---
title: "WP1 Sea Ice Code Development — Optimization"
draft: false
featured: true
weight: 1
heroSubHeading: 'SEA ICE CODE DEVELOPMENT AND OPTIMIZATION'
---

Our ambition is to develop of the neXtSIM sea ice model to run on massively parallel architectures, making its inclusion in an Earth System Model feasible. To accomplish this we will improve the numerical efficiency of its underlying C++ code and perform exploratory work to enable continued improvements in model efficiency beyond those immediately necessary for integrating it into a climate model. 

WP1 is divided into five tasks, two of which address known shortcomings of the current model version, two which aim to push the numerical performanc eof the model further and one concerned with evaluating the physical consistency of the results obtained with the updated model code.

 - Discontinuous galerkin implementation into neXtSIM
 - General code optimizations, improvements, and documentation
 - Investigation of the applicability of the phase field method for solving the sea ice rheology 
 - Investigation of the potential for GPU acceleration
 - Evaluation of the optimized code

 People involded in WP1 :

 - Einar Ólason (einar.olason(at)nersc.no)
 - Véronique Dansereau (veronique.dansereau(at)univ-grenoble-alpes.fr)
 - Pierre Saramito (pierre.saramito(at)math.cnrs.fr)
 - Jérome Weiss (jerome.weiss(at)univ-grenoble-alpes.fr)
 - Pierre Rampal (pierre.rampal(at)univ-grenoble-alpes.fr)
 - Chris Horvat (christopher_horvat(at)brown.edu)
 - Clément Rousset (clement.rousset(at)locean.ipsl.fr)
 - Martin Vancoppenolle (martin.vancoppenolle(at)locean.ipsl.fr)
