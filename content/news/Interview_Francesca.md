---
title: 'Interview with Francesca Vittorioso, Postdoc, University of Bologna'
date: 2024-02-06
authors:
categories: ['Interviews']
description: Francesca has recently joined our team to work on Data Assimilation. On the occasion of her upcoming webinar, she accepted to share some of her personnal history and scientific background. 
thumbnail: 'images/news/Interview_Francesca'
heroBackground: '/images/ice-bandeau.png'
---

 Francesca Vittorioso, postdoc at the University of Bologna, Italy, recently joined SASIP to work on Data Assimilation. On February 21st, she will give a webinar [(register here)](https://forms.gle/YKoBQK3XBLgjULnr6) presenting her latest research on the Contribution of the assimilation of MTG/IRS radiances for the characterisation of the atmospheric chemical composition over Europe. On this occasion, we asked her to share some of her personal and scientific history. 

> "SASIP will allow a better understanding of the warming of the polar regions. Given the historical moment that planet Earth is currently > > experiencing, I find this a study with excellent motivation and potential".

_An interview with Francesca Vittorioso, Postdoc at the University of Bologna_.

_By: Solène Guyard_.

_Monday, February 5, 2024_.


**How did you become a scientist?**

I would start by saying that I was born and grew up in Tropea, a beautiful town in Southern Italy surrounded by an immense natural beauty. This led me to have an interest in the study of physical phenomena, with a particular focus on physics of the Earth system and space. After a high school education in science, I then completed a Bachelor's degree in Physics at the University of Calabria. After that I proceeded my academic career in the University of Bologna, where I took a Master's degree in Atmospheric Physics and Meteorology. 

Motivated by a keen interest in remote sensing, I sought out projects that would allow me to get involved in it. I have been lucky enough to be selected for a 3-year position in Toulouse at the CNRM[^1], which is a joined unit of CNRS[^2] and Météo-France[^3], on a project founded by the CNES[^4]. This position was focused on preparing the arrival of a new generation of the Infrared Atmospheric Sounding Interferometer (IASI-NG), a key payload of the Metop Second Generation satellites (METOP-SG) series, designed to feed operational weather forecasting centers, the Copernicus Services and the entire scientific community (given also its immense potential in atmospheric chemistry monitoring).  During those 3 years, I was in charge of selecting IASI-NG channels for the assimilation in Numerical Weather Prediction models. I got on so well in the working environment of the CNRM in Toulouse that I decided to do a PhD there.

The objective of my PhD work (cofounded by Méteo-France and Thales Alenia Space) was, in basic terms, to study the contribution that the assimilation of data from InfraRed Sounder (IRS), that will fly on board MTG, could make in the characterization of the atmospheric chemical composition over Europe (more details in the point below).

I earned my PhD in April 2023. After seven years in France, however, the desire to put the skills acquired abroad to good use in my home country became strong. That is how I landed in the SASIP team. Although not completely in line with what I did in the previous part of my career, this job is very interesting to me because it will make me broaden my skills. I will be dealing with data assimilation (for which I was trained), but applied to a domain that is new to me, namely sea-ice.

**What was the context of the research you will present on February 21st?**

In the coming years, EUMETSAT’s Meteosat Third Generation - S (MTG-S) satellites will be launched with an instrument of valuable features on board. The MTG - Infrared Sounder (IRS) will represent a major innovation for the monitoring of the chemical state of the atmosphere, since, at present, observations of these parameters mainly come from in situ measurements (geographically uneven) and from instruments on board of polar-orbiting satellites (highly dependent on the scanning line of the satellite itself, which is limited, over a specific geographical area, to very few times per day). 
MTG-IRS will present many potentialities in the area of detecting different atmospheric species and will have the advantage of being based on a geostationary platform and to acquire data with a high temporal frequency (every 30 minutes over Europe), which makes easier to track, among the others, the transport of the species of interest.

This has been the context for the research to carry on, which aimed to evaluate the impact of the assimilation of IRS radiances within a chemical transport model (CTM), such as the Modèle de Chimie Atmosphérique de Grande Echelle (MOCAGE), i.e. the CTM operational in Météo-France.

While MTG-IRS is still being built and validated by Thales Alenia Space, which is in charge of its development, the future is already being explored. An IRS instrument with very similar characteristics to the first one, but with a better spectral sampling (namely 0.325 cm−1 vs the 0.605 cm−1 of the first version) has been studied. The second objective of the project was, therefore, to assess the different contributions that the two instrument versions could possibly make in providing atmospheric composition information when assimilated into a CTM such as MOCAGE.
In order to make this evaluation, IRS observations (for both its studied versions) had to be simulated as accurately as possible since IRS is not yet in orbit, and its version with a higher spectral sampling is still being evaluated. To do so, the Observing System Simulation Experiment (OSSE) method was exploited. Of the species to which IRS will be sensitive, the one treated along this study was ozone. However, the groundwork has been laid in order to be able to extend the research to other species in any work that will follow this thesis.

**You have recently joined SASIP. What dimension of the project are you involved in?**

The Scale-Aware Sea-Ice Project (SASIP) is a project whose main aim is to develop an innovative sea-ice model for climate research and, more specifically, for the better understanding and predicting the rapid changes caused by the warming of the polar regions.

This is done through the development of a new version of the model neXtSIM, which is constantly being updated with the implementation of advanced techniques, novel numerical approximation for its numerical core and optimization of its parameters, and via modern data assimilation (this is at the core of my specific task) and machine learning techniques. 

[Five working packages](https://sasip-climate.github.io/research/) coexist in SASIP. Each of them is set up to develop a specific research step in strong synergy across them. My postdoctoral research is part of the [Work Package 4](https://sasip-climate.github.io/research/work-package-four/), which deals with developing novel and targeted Data Assimilation (DA) and machine learning techniques adapted to the continuum version of the model neXtSIM. 

Specifically, I am working on coupling the new version of neXtSIM, named neXtSIM_DG in view of the use of a discontinuous Galerkin numerical core, to an ensemble Kalman filter. This will bring to the assimilation of observations (primarily satellite ones) in neXtSIM_DG to infer its state and its parameters. 

My work will take off from two studies produced in SASIP to date. In the first one[^5] the ensemble variational method IEnKF has been used to estimate the state and the parameters in the dynamics-only sea-ice model[^6] that uses both a rheology and a numerical core like neXtSIM_DG. The second one[^7] proposes a fully innovative approach to tailor DA to DG models, that makes possible to assimilate denser data than before, thus potentially better exploiting satellite measurements. 

I will be working in close collaboration with other SASIP members, among which Ali Aydogdu (CMCC)[^8] and Yue Ying (NERSC)[^9]. We plan to use the python EnKF package, NEDAS, recently developed at NERSC.

**What made you join SASIP? What aspect of the project do you appreciate most?**

The SASIP project impressed me very early on with its international connotation. I really like the fact that so many people with different backgrounds and based in different research centers are able to coordinate to collaborate and produce a quality product. 
Plus, SASIP will allow a better understanding of the warming of the polar regions. Given the historical moment that planet Earth is currently experiencing, I find this a study with excellent motivation and potential.

Personally, I felt I should apply for the position I am currently in, because it will allow me to use my skills in Data Assimilation. At the same time, however, as you may have deduced, I have never worked on sea ice. This is very challenging for me from a scientifical point of view. I am intrigued by the idea of studying and learning something new about scientific aspects that were only dealt with during my studies.


[^1]:French National Center for Meteorological Research_. 
[^2]:French National Centre for Scientific Research_.
[^3]:French National Meteorological Service_.
[^4]:French Space Agency_.
[^5]:Cheng et al., 2024_.
[^6]:Dansereau, 2016_.
[^7]:Pasmans et al., 2024_. 
[^8]:Euro-Mediterranean Center on Climate Change, SASIP partner, Italy
[^9]:Nansen Environmental and Remote Sensing Center, SASIP partner, Norway
