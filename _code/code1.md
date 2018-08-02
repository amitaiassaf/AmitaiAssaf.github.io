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
  
Affinity maturation drives evolutionary constraints on virus spike density
======

The spikes on virus surfaces bind receptors on host cells to propagate infection. High spike densities (SDs) can promote infection, but spikes are also targets of antibody-mediated immune responses. Thus, diverse evolutionary pressures can influence virus SDs. HIV’s SD is about two orders of magnitude lower than that of other viruses, a surprising feature of unknown origin. By modeling antibody evolution through affinity maturation, we find that an intermediate SD maximizes the affinity of generated antibodies. We argue that this leads most viruses to evolve high SDs. T helper cells, which are depleted during early HIV infection, play a key role in antibody evolution. We find that T helper cell depletion results in high affinity antibodies when SD is high, but not if SD is low. This special feature of HIV infection may have led to the evolution of a low SD to avoid potent immune responses early in infection. 

Enconter events in biology
======
The DNA is subject to Brownian motion resulting from the interactions with the surrounding water molecules and is constantly moving inside a confined domain, which is determined by the cell or nucleus membrane. In recent years it has been understood that its dynamics and organization have significant consequences on the cellular functions. For example, the encounter between chromosome sites is directly involved in many biological processes, such as gene regulation and DNA repair. One important characteristic of these encounter events is their frequency. Since the interacting sites have to come to a close proximity for the chemical interaction to occur and because the encounter is largely diffusion limited, these events are inherently rare. The exact implications of these encounter events are still mostly unknown, but over the last decade microscopy methods and chromosome capture techniques have been developed for their study.

I have used simple models to study encounter between chromatin sites in different scenarios. We first addressed the question of the encounter between two monomers part of the long chain in bulk (DNA looping). We have found for the first time, a complete mathematical formula describing the dependency of the mean encounter time, on the length of the polymer chain and the capture radius, which is the distance at which the sites meet. In a second work, we have looked at the way these rates change when the polymer chain is confined in a close domain representing the nucleus, or a chromosome domain. We found an analytical formula describing the dependency of this rate on the size of the domain. Interestingly, we find that encounter and looping can be very effectively regulated by controlling the domain size.

[Analysis of the mean first looping time of a rod-polymer](http://epubs.siam.org/doi/abs/10.1137/110842624)

[Computation of the Mean First-Encounter Time Between the Ends of a Polymer Chain](http://journals.aps.org/prl/abstract/10.1103/PhysRevLett.109.108302)

[Diffusing Polymers in Confined Microdomains and Estimation of Chromosome Territory Sizes from Chromosome Capture Data](http://journals.aps.org/prl/abstract/10.1103/PhysRevLett.110.248105)

[A link to a talk I gave about polymer looping](http://www.birs.ca/events/2015/5-day-workshops/15w5110/videos/watch/201503251043-Amitai.html)

