---
title: "OpenSAFT: an extensible Julia implementation of SAFT‐type equations of state"
collection: talks
type: "Poster"
permalink: /talks/2021-07-08-Post-ESAT2021_Clapeyron
venue: "ESAT 2021 - 31st European Symposium on Applied Thermodynamics"
date: 2021-07-07
location: "Online"
---
The venerable Statistical Associating Fluid Theory (SAFT) equation of state has always had the reputation of being abstruse and impenetrable to the outside world—and to those working in the field, they are often stuck working with complicated legacy code. OpenSAFT.jl is a modern thermodynamics framework built in pure Julia for the full process of implementation and use of SAFT-type (or any free energy-based) models in an easy and intuitive way. 

We currently support 14 variants of the SAFT equation, including SAFT-γ Mie, PC-SAFT, soft-SAFT, and the original 1990 SAFT equation by Chapman et al., along with 5 standard cubic equations of state, all complete with an extensive database of published parameters (and allow for user-specified parameters to be implemented). We take full advantage of robust community-supported tools in the Julia ecosystem such as automatic differentiation, optimisation and numerical solver packages to determine a range of bulk and phase-equilibrium properties (using methods such as the HELD algorithm).  OpenSAFT.jl is easily extensible to allow users to test their own thermodynamic models, whether they be wholly original or based on a pre-existing model, using the in-built property estimation methods (as long as these are SAFT-based or cubic-based). We hope to highlight that the implementation of thermodynamic models can be both lucid and computationally efficient.