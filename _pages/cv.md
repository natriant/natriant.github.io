---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* PhD in Accelerator Physics, University of Liverpool, United Kingdom, 11/2018-02/2023
* Bachelor  in Physics, Aristotle University of Thessaloniki, Greece  , 09/2013-10/2018
* Erasmus+ Exchange, University of Łódź, Poland , 02/2017-06/2017

Work experience
======
* Senior Fellow - CERN, Geneva, Switzerland, 12/2022 to Present
  * LHC Collimation and Ion Operation: Simulations, Operation, Data Analysis
  * Optics validation, beam loss analysis, machine commissioning, and machine studies
  * Beam-detector interface effects: beam-halo and background formation; student supervision
  * Luminosity and beam evolution analysis in Python for ion runs (O-O, p-O, Ne-Ne, Pb-Pb)
  * Machine optimisation for multiple ion species; match experiment targets; results guiding approval of future physics programs

* PhD Student - CERN, Geneva, Switzerland, 11/2018-11/2022
  * Studied effect of RF noise in the HL-LHC crab cavities on transverse emittance through beam-dynamics simulations (impedance, non-linearities, RF noise)
  * Beam element modelling (PyHEADTAIL and SixTrackLib)
  * Experimental crab cavity beam tests in SPS

* Technical Student - CERN, Geneva, Switzerland, 10/2017-11/2018
  * Investigated sources of SPS emittance growth, focusing on magnet non-linearities and power supply ripples
  * Built and validated non-linear MAD-X model for tracking in SixtTrack
  * Large scale simulation campaigns for Dynamic Aperture and Frequency Map Analysis
  * Developed a custom tracking code: study noise & non-linear effects on phase space and tune shifts
  


Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  

