---
layout: archive
title: "Natalia Triantafyllou"
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
 
Programming and Software
======
* Programming: Python (e.g. numpy, scipy, pandas, matplotlib, PySpark, Git)
* Simulation tools: MAD-X, Xsuite, PyHEADTAIL, SixTrack/SixDesk, SixTrackLib, Collider Time Evolution (CTE)

Languages
======
* Greek: Native  
* English: Proficient User (C2)
* French: Independent User (B1)

Detailed Professional Experience
======
**Experimental Work**
* Validating measured distribution of beam losses around the LHC ring, sign-off on performance of the collimation system
* Performance analysis of the Pb-Pb ion runs (2023, 2024) and light ions (2025): intensity, transmission, emittance, bunch length, luminosity production, comparison with simulations
* Assessing Beam Loss Monitor thresholds for different machine configurations
* Correlated beam-induced background in LHC experiments with beam losses and collimator settings
* Planned, performed, and post-processed machine studies e.g. improving collimator settings, minimising losses at injection plateau
* Benchmarked coherent tune shift from beam coupling impedance against theoretical predictions and simulations

**Simulation Work**
* Collimation simulations in LHC (Xsuite): combined particle tracking and particle-matter interaction simulations
* Simulation of beam-halo effects on detectors i.e. ATLAS, PPS XRP (Xsuite)
* Beam property evolution (emittance, losses) and luminosity in physics fills (CTE); including space charge, radiation damping, luminosity burn-off etc
* Beam stability and emittance growth  in the presence of beam-coupling impedance, RF noise and non-linearities; coherent/incoherent tune shifts, damping mechanisms (PyHEADTAIL)
* Non-linear beam dynamics simulations: Dynamic Aperture, Frequency Map Analysis, and phase space studies for a non-linear SPS lattice (built in MAD-X) considering magnet non-linearities and power supply ripples
* Modelling of phase and amplitude noise (PyHEADTAIL), implementation of crab cavity element (in SixTrack)
* Converted measured spectra to discrete time series for use in simulations

**Hardware and Operation**
* Measured transverse emittance in SPS with Wire Scanners, beam losses, and aperture in LHC 
* Set up and aligned collimators, monitor motor drifts during operation, applied trimming knobs through LHC Software Architecture (LSA), configure LHC and SPS kickers for beam excitation
* Retrieved and analysed data from various beam diagnostic instruments, including:
  * Wire Scanners and LHC Synchrotron Light monitor (BSRT) for emittance measurements
  * LHC Head-Tail Monitor, wide-band beam position monitor, to measure intra-bunch beam position for crab cavity diagnostics
  * Spectrum analyser
  * Beam Quality Monitor (BQM) and Wall Current Monitors for the longitudinal beam quality
  * Beam Loss Monitors (BLMs) for loss evaluation
  * Fast Beam Current Transformers (FBCT) for beam and bunch by bunch intensity measurements
  * Vacuum gauges and equipment temperature readings 



Publications
======
Find my articles on my [ORCID profile.](https://orcid.org/0000-0001-6651-9532)

  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  

