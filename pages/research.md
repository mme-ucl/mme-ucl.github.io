---
layout: page
title: Research
permalink: /research
---


### Theory and Simulations of Nucleation
Nucleation is a rare event marking the emergence of new materials. Understanding the physicochemical mechanisms for nucleation of liquids and crystals is important to control these processes and determine their rates. In MME, we develop and apply enhanced sampling techniques to simulate nucleation and overcome the timescale challenges associated with these types of simulations. Importantly, we have developed methods that allow us to overcome the finite size effects apparent in molecular simulations that affect the determination of nucleation rates and perturb the phase behaviour of nucleating systems.

_Relevant Publications_: 

### Crystallization Collective Variables
Nucleation, as previously mentioned, is a challenging problem to study computationally. In this group, we employ enhanced sampling methods that push the system toward nucleation in one way or another. However, an interesting research question here is, what is this direction? Typically, this direction is expressed as a mathematical function approximating the system's degree of order/crystallinity. Such a function needs to be able to deal with all the complexities inherent to the nucleation problem at hand while, at the same time, being as computationally efficient as possible. Finding this compromise is challenging and an ongoing area of research in this group.

_Relevant Publications_: 

### Conformational Flexibility of Organic Molecules in Solution
We harness the power of unsupervised clustering to untangle the conformational complexity of highly flexible drug molecules. Using data generated from enhanced sampling molecular dynamics simulations, the endless number of contortions undertaken by a molecule in solution can be refined into a set of key conformers. The relative population of these conformers evolve as the system moves from the solution to the crystal phase, allowing us to trace the path taken by the molecule as it settles into its position in the lattice.

_Relevant Publications_: 

### Beyond Lattice Energy landscapes in Crystal Structure Prediction
Many active pharmaceutical ingredients (API) exhibit polymorphism at room conditions in the solid phase. Awareness of relative persistence of different forms at different physical conditions is important for many reasons within the pharmaceutical industry. In this regard, our group is looking towards expanding the PyPol methodology beyond unsupervised clustering and identification of metastable forms using CSP and MD simulations, towards the development of novel algorithms which could analyse this data and compete with the classical entropy estimation methods in both computational cost and accuracy.

### Machine Learning
In line with recent trends in scientific research, part of our method development efforts focuses on machine-learning/data-based approaches.  We aim to combine modern machine-learning techniques with a deep understanding of the underlying physics, to push the limits of modern simulation and modelling techniques.

_Relevant Publications_: 

### Enhanced Sampling
Molecular simulations provide the tools to study how the structural evolution of a collection of molecules give rise to macroscopic material properties, such as crystal habits and polymorphism. The timescales over which processes such as self-assembly, crystal growth and dissolution occur are typically far beyond the microsecond capabilities of standard molecular dynamics. Enhanced sampling simulations circumvent these challenges by, for example, biasing the potential energy landscape to force the system to sample regions of collective variable space that would otherwise be visited with very low probability. In MME, we develop and apply enhanced sampling methods such as metadynamics and umbrella sampling to simulate activated assembly to gain mechanistic insight and rates for these processes.

See our recent work in this area:
Modeling the Structure and Interactions of Intrinsically Disordered Peptides with Multiple Replica, Metadynamics-Based Sampling Methods and Force-Field Combinations
Molecular Level Understanding of the Free Energy Landscape in Early Stages of Metal–Organic Framework Nucleation

 
### Controlling Chemical Potential in finite-sized simulations
Molecular dynamics simulations are usually performed using a constant number of molecules. In processes such as adsorption, crystal nucleation and dissolution, the transfer of molecules to/from a solid phase changes the number of molecules in the surrounding medium, resulting in an evolving chemical potential for this phase and shifting the driving force for the process of interest. These changes can affect the rates and molecular mechanisms we wish to investigate. Our group, along with our collaborators, have developed a method called constant chemical potential molecular dynamics (CμMD) to maintain a constant composition fluid phase in non-equilibrium simulations. The method makes use of an internal reservoir which adds or removes molecules to a fluid medium as the concentration of these species is changed by the presence of a solid-fluid interface, allowing us to understand the properties of an evolving interface that can be accurately compared to experiments.
See our recent work that exploits the capabilities of CμMD:
Electrochemistry, ion adsorption and dynamics in the double layer: a study of NaCl(aq) on graphite
Bridging the gap between mesoscopic and molecular models of solid/liquid interfaces out-of-equilibrium

 
### Crystal Structure Prediction

Different packings of the same molecule (polymorphism) can lead to different physical properties, such as melting point, hygroscopicity and bioavailability. This can cause problems for the effectiveness of many materials, particularly pharmaceuticals. Hence it is very important for industry to know which polymorphs are likely.
Crystal Structure Prediction (CSP) generates energy/structure/function landscapes of hypothetical crystal structures. These structures are ranked based on their lattice energy, with the most stable being the most likely to form. Energy landscapes (such as the one pictured) often have many more hypothetical crystal structures than observed polymorphs, but are still useful in assessing the experimental solid form landscape for small pharmaceuticals, such as galunisertib or ibuprofen.
