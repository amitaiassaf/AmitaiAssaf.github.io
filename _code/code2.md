---
layout: archive
title: "CV"
permalink: /cv/
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


Work experience
======
* Summer 2015: Research Assistant
  * Github University
  * Duties included: Tagging issues
  * Supervisor: Professor Git

* Fall 2015: Research Assistant
  * Github University
  * Duties included: Merging pull requests
  * Supervisor: Professor Hub
  
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
