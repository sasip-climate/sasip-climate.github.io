---
title: 'Towards a GPU-Parallelization of the neXtSIM-DG Dynamical Core'
date: 2024-02-28
authors:
categories: ['Publications']
description: 'New preprint by Jendersie et al.'
thumbnail: '/images/news/Jendersie_Preprint_2024.png'
image: '/images/news/Jendersie_Preprint_2024.png'
heroBackground: '/images/ice-bandeau.png'
---

Towards a GPU-Parallelization of the neXtSIM-DG Dynamical Core by Jendersie et al. 

In recent years, a number of frameworks have become available that promise to simplify general purpose GPU programming. In [**this new preprint**](https://arxiv.org/abs/2402.00466), Robert Jendersie and colleagues compare multiple such frameworks, including CUDA, SYCL, Kokkos and PyTorch, for the parallelization of \nextsim, a finite-element based dynamical core for sea ice. They evaluate the different approaches according to their usability and performance.

https://doi.org/10.48550/arXiv.2402.00466 

---

![[Jendersie2024](https://arxiv.org/abs/2402.00466)](/images/news/Jendersie_Preprint_2024.png)

---
_[**Fig.2** (from Jendersie et al.)]([https://arxiv.org/abs/2402.00466]):Timings of the stress update using the best performing version for each framework. The size of the mesh cells size is scaled from \qty4km to \qty0.25km while keeping the domain size constant to increase the number of elements. Dashed variants are run with lower floating-point precision_.
