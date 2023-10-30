---
layout: post
title: Controlling Chemical Potential in finite-sized simulations with CμMD
---

<img src="https://github.com/mme-ucl/mme-ucl.github.io/raw/main/images/cmumd.png" align="center" width="800px"/>

Molecular dynamics simulations are usually performed using a constant number of molecules. In processes such as adsorption, crystal nucleation and dissolution, the transfer of molecules to/from a solid phase changes the number of molecules in the surrounding medium, resulting in an evolving chemical potential for this phase and shifting the driving force for the process of interest. These changes can affect the rates and molecular mechanisms we wish to investigate. Our group, along with our collaborators, have developed a method called constant chemical potential molecular dynamics (CμMD) to maintain a constant composition fluid phase in non-equilibrium simulations. The method makes use of an internal reservoir which adds or removes molecules to a fluid medium as the concentration of these species is changed by the presence of a solid-fluid interface, allowing us to understand the properties of an evolving interface that can be accurately compared to experiments.
CμMD has been employed to investigate crystal growth, nucleation, membrane-based separations, and electrochemical interfaces. 

_Method Papers:_ 
- [Molecular dynamics simulations of solutions at constant chemical potential, C Perego, M Salvalaglio, M Parrinello, The Journal of chemical physics 142 (14), 2015.](https://pubs.aip.org/aip/jcp/article/142/14/144113/898424/Molecular-dynamics-simulations-of-solutions-at)
- [Concentration gradient driven molecular dynamics: a new method for simulations of membrane permeation and separation
A Ozcan, C Perego, M Salvalaglio, M Parrinello, O Yazaydin, Chemical science 8 (5), 3858-3865, 2017](https://pubs.rsc.org/en/content/articlehtml/2017/sc/c6sc04978h) 

_Applications to electrochemical interfaces:_ 
- [Constant chemical potential–quantum mechanical–molecular dynamics simulations of the graphene–electrolyte double layer
N Di Pasquale, AR Finney, JD Elliott, P Carbone, M Salvalaglio, The Journal of Chemical Physics 158 (13), 2023](https://pubs.aip.org/aip/jcp/article/158/13/134714/2883280/Constant-chemical-potential-quantum-mechanical)
- [Properties of aqueous electrolyte solutions at carbon electrodes: effects of concentration and surface charge on solution structure, ion clustering and thermodynamics in the electric double layer. AR Finney, M Salvalaglio, Faraday Discussions	2023](https://pubs.rsc.org/en/content/articlehtml/2023/fd/d3fd00133d)
- [Bridging the gap between mesoscopic and molecular models of solid/liquid interfaces out-of-equilibrium
AR Finney, M Salvalaglio, Chemical Engineering Research and Design 180, 285-295, 2022](https://www.sciencedirect.com/science/article/pii/S0263876222000727)
- [Electrochemistry, ion adsorption and dynamics in the double layer: a study of NaCl(aq) on graphite. AR Finney, IJ McPherson, PR Unwin, M Salvalaglio, Chemical Science 12, 11166-11180, 2021](https://pubs.rsc.org/en/content/articlehtml/2021/sc/d1sc02289j)

_Review:_ 
- [Non-Equilibrium Modeling of Concentration-Driven processes with Constant Chemical Potential Molecular Dynamics Simulations
T Karmakar, AR Finney, M Salvalaglio, AO Yazaydin, C Perego Accounts of Chemical Research 56 (10), 1156-1167, 2023.](https://pubs.acs.org/doi/abs/10.1021/acs.accounts.2c00811)

[_Source code for PLUMED2_](https://github.com/mme-ucl/CmuMD)

[_Tutorial @ PLUMED school_](https://plumed-school.github.io/lessons/22/008/data/NAVIGATION.html)
