---
layout: archive
title: "Code"
permalink: /code/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Modeling chromatin dynamics
======
* B.S. in Github, Github University, 2012
* M.S. in Jekyll, Github University, 2014
* Ph.D in Version Control Theory, Github University, 2018 (expected)

A common approach to study chromatin dynamics is to tag it with a fluorescent mark and follow 
its motion inside the nucleus with a confocal microscope. The end result is a long trajectory. 
A chromatin locus performs complicated stochastic trajectory. We have developed a method to analyze such trajectories.

In a new paper published in cell reports (Amitai, Assaf et al. Cell Reports, 18, 1200 - 1214, 2017), we describe a statistical 
method to estimate four parameters characterizing chromatin dynamics from Single Particle Trajectories (SPTs). 
We provide here our Matlab code to study the time-lapse imaging of single loci by fluorescence microscopy. 
The code can be applied to any trajectories of tagged DNA loci. 
The code allows extracting four biophysical parameters from the movement. 
The method can be used to study the changes following DNA damages or breaks and can be applied to single locus trajectories in any species.


A population dynamics model for clonal diversity in a germinal center
======
* Summer 2015: Research Assistant
  * Github University
  * Duties included: Tagging issues
  * Supervisor: Professor Git

* Fall 2015: Research Assistant
  * Github University
  * Duties included: Merging pull requests
  * Supervisor: Professor Hub
  
Germinal centers (GCs) are micro-domains where B cells mature to develop high affinity antibodies. The GC is seeded by multiple (~50-200) initial B cell clones. Each clone has a unique sequence of the gene coding for the B cell receptor (BCR). This receptor later becomes the antibody in mature B cells capable of binding and neutralizing an antigen. During the germinal center reaction, B cell clones proliferate and create diverse lineages, where the descendent self-induce somatic hyper-mutations. Inside a GC, B cells compete for antigen and T cell help, and the successful ones continue to evolve and become memory and plasma B cells. We studied the competition between B cell clone using a simple population dynamics model of birth/death and mutation. We find that, like all evolutionary processes, diversity loss is inherently stochastic. We study two selection mechanisms, birth-limited, and death limited selection. While death limited selection maintains diversity and allows for slow clonal homogenization as affinity increases, birth limited selection results in a rapid takeover of successful clones.
  
  
Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams
