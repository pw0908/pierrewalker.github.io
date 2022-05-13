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
* California Institute of Technology, US: Ph.D in Chemical Engineering, 2021-present (4.2 GPA)
* Massachusetts Institute of Technology, US: Major in Chemical Engineering, 2019-2020 (5.0 GPA)
* Imperial College London, UK: M.Eng in Chemical Engineering, 2017-2021 (81.7% average)
* St. Andrews GV, Thailand: IB certification, 2010-2017 (43 points)

Work experience
======
* Centre for Energy Resources Engineering (2020-2021): Visiting researcher
  * Technical University of Denmark
  * Project: Compared various models of electrolyte mixtures and studied of the importance of the dielectric constant in these models. Also developed a brand-new combining rule to obtain parameters a priori for electrolyte systems in SAFT-VR Mie. 
  * Supervisor: Professor Kontogeorgis and Professor Liang

* Green Research Group (2019-2021): Undergraduate Researcher
  * Massachusetts Institute of Technology
  * Project: Improved the modelling of solvation properties within the Reaction Mechanism Generator (RMG) through group additivity methods to be used in the estimation of liquid-phase kinetics. Compared these methods to Machine Learning alternatives. Also performed a comparison between predictive thermodynamic models: SAFT-γ Mie and COSMO-RS.
  * Supervisor: Professor Green and Yunsie Chung

* Matar Fluids Group (2019-2021): Undergraduate Researcher
  * Imperial College London 
  * Project: Built a framework to solve the Cahn-Hilliard system of equations to model the spinodal decomposition of polymers using advanced thermodynamic models. The framework has successfully modelled systems using PC-SAFT, UNIFAC-FV and the Flory-Huggins equation. It has also been made available open source.
  * Supervisor: Professor Matar and Dr. Haslam

* Molecular Systems Engineering Research Group (2018-2021): Undergraduate Researcher
  * Imperial College London 
  * Project: Developed a new approach to modelling the ideal free energy, for use with SAFT (a state-of-the-art equation of state) to improve the modelling of thermal properties. Also performed an extensive study of the role of the ideal term in the overall equation of state.
  * Supervisor: Dr. Haslam

* StudentShapers (2018-present): Student Partner
  * Imperial College London 
  * Project: As part of the student-staff partnership programme, undertook a variety of pedagogical projects:
    * Constructed and maintained a student-led chemical engineering wiki for the undergraduate cohort at Imperial.
    * Developed and tested an accelerated course on Solidworks for undergraduate chemical engineers to be incorporated into an existing course module.
    * Evaluated the role of student-led maker spaces in engineering education and how these may be facilitated or incentivised.
  * Supervisor: Dr. Maraj

* Qatar Carbonates and Carbon Storage Research Centre (2018): Undergraduate Researcher
  * Imperial College London 
  * Project: Modelled thermal behaviour of mixture cyclic alkanes, water and carbon dioxide. Sponsored by the QCCSRC.
  * Supervisor: Professor Galindo and Dr. Haslam
  
Skills
======
* Computer Coding:
  * MATLAB
  * Python
  * LaTeX
  * Julia
  * C++/CUDA
* Advanced Research Software
  * Quantum Chemistry: ORCA, Jaguar
  * Process Simulator: gPROMS, ASPEN
  * Molecular Dynamics: GROMACS, LAMMPS
  * GAMS
  * Solidworks
  * COSMOtherm
* Languages:
  * English
  * French

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

