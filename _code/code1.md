---
layout: archive
title: "Code"
collection: code
permalink: /code/
author_profile: true
---

{% include base_path %}

Modeling chromatin dynamics
======

A common approach to study chromatin dynamics is to tag it with a fluorescent mark and follow 
its motion inside the nucleus with a confocal microscope. The end result is a long trajectory. 
A chromatin locus performs complicated stochastic trajectory. We have developed a method to analyze such trajectories.

In a new paper published in cell reports (Amitai, Assaf et al. Cell Reports, 18, 1200 - 1214, 2017), we describe a statistical 
method to estimate four parameters characterizing chromatin dynamics from Single Particle Trajectories (SPTs). 
We provide here our Matlab code to study the time-lapse imaging of single loci by fluorescence microscopy. 
The code can be applied to any trajectories of tagged DNA loci. 
The code allows extracting four biophysical parameters from the movement. 
The method can be used to study the changes following DNA damages or breaks and can be applied to single locus trajectories in any species.

[Download code here](https://github.com/amitaiassaf/SPT_analysis)

A population dynamics model for clonal diversity in a germinal center
======
  
Germinal centers (GCs) are micro-domains where B cells mature to develop high affinity antibodies. The GC is seeded by multiple (~50-200) initial B cell clones. Each clone has a unique sequence of the gene coding for the B cell receptor (BCR). This receptor later becomes the antibody in mature B cells capable of binding and neutralizing an antigen. During the germinal center reaction, B cell clones proliferate and create diverse lineages, where the descendent self-induce somatic hyper-mutations. Inside a GC, B cells compete for antigen and T cell help, and the successful ones continue to evolve and become memory and plasma B cells. We studied the competition between B cell clone using a simple population dynamics model of birth/death and mutation. We find that, like all evolutionary processes, diversity loss is inherently stochastic. We study two selection mechanisms, birth-limited, and death limited selection. While death limited selection maintains diversity and allows for slow clonal homogenization as affinity increases, birth limited selection results in a rapid takeover of successful clones.

[Download code here](https://github.com/amitaiassaf/Modeling-Germinal-Center-Reaction)

https://github.com/amitaiassaf/Modeling-Germinal-Center-Reaction
  
  
Affinity maturation drives evolutionary constraints on virus spike density
======

The spikes on virus surfaces bind receptors on host cells to propagate infection. High spike densities (SDs) can promote infection, but spikes are also targets of antibody-mediated immune responses. Thus, diverse evolutionary pressures can influence virus SDs. HIV’s SD is about two orders of magnitude lower than that of other viruses, a surprising feature of unknown origin. By modeling antibody evolution through affinity maturation, we find that an intermediate SD maximizes the affinity of generated antibodies. We argue that this leads most viruses to evolve high SDs. T helper cells, which are depleted during early HIV infection, play a key role in antibody evolution. We find that T helper cell depletion results in high affinity antibodies when SD is high, but not if SD is low. This special feature of HIV infection may have led to the evolution of a low SD to avoid potent immune responses early in infection. 

* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3

Service and leadership
======
* Currently signed in to 43 different slack teams
