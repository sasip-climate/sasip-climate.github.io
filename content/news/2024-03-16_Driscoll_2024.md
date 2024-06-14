---
title: 'Parameter sensitivity analysis of a sea ice melt pond parametrisation and its emulation using neural networks'
date: 2024-03-16
authors:
categories: ['Publications']
description: 'New Article by Simon Driscoll et al.'
thumbnail: '/images/news/Driscoll_2024.png'
image: '/images/news/Driscoll_2024.png'
heroBackground: '/images/ice-bandeau.png'
---

[**Parameter sensitivity analysis of a sea ice melt pond parametrisation and its emulation using neural networks**](https://doi.org/10.1016/j.jocs.2024.102231) by Simon Driscoll, Alberto Carrassi, Julien Brajard, Laurent Bertino, Marc Bocquet, Einar Örn Ólason, published in the Journal of Computational Science. 

Simon Driscoll et al. show through a global sensitivity analysis and analysis of perturbed parameter ensembles that a state-of-the-art sea ice model, Icepack, demonstrates a substantial sensitivity to its level-ice melt pond parametrisation. To reduce this uncertainty, they investigated the possibility of data driven approaches to learn and replace parametrisations. Neural networks were able to learn offline a parametrisation and this was coupled to the Icepack model in place of the melt pond parametrisation, running online without substantial drift or instabililty for many years. This result paves the way for incorporating observationally based data driven melt pond emulators in sea ice and climate models.

https://doi.org/10.1016/j.jocs.2024.102231

---

![[Driscoll2024](https://doi.org/10.1016/j.jocs.2024.102231)](/images/news/Driscoll_2024.png)

---
_[**Fig.9** (from Driscoll et al.)]([https://www.sciencedirect.com/science/article/pii/S1877750324000243?via%3Dihub]):Time series of error for linear regressions and neural networks, both compared to the physical MPP for key output variables. Shading represents one standard deviation width above and below the mean solid lines. (NB: SIAF  “Sea ice area fraction”; AIT “Average Ice Thickness”; PA  “Pond Albedo”; EPA  “Effective Pond Albedo”)_. 
