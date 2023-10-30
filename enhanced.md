---
layout: post
title: Enhanced Sampling Method Development
---

<video src="https://github.com/mme-ucl/mme-ucl.github.io/raw/main/images/MFI_movie.mp4" align="center" width="1000px" controls></video>

Molecular simulations provide the tools to study how the structural evolution of a collection of molecules gives rise to macroscopic material properties, such as crystal habits and polymorphism. The timescales over which processes such as self-assembly, crystal growth, and dissolution occur are typically far beyond the microsecond capabilities of standard molecular dynamics. Enhanced sampling simulations circumvent these challenges by, for example, biasing the potential energy landscape to force the system to sample regions of collective variable space that would otherwise be visited with very low probability. We develop and apply enhanced sampling methods such as metadynamics and umbrella sampling to simulate activated assembly to gain mechanistic insight and rates for these processes. 
In this context, we have developed methods to assess the quality of rate estimates from metadynamics simulations, to map entropic and enthalpic contributions in collective variable spaces, and to use thermodynamic integration to reconstruct free energy surfaces from asynchronous metadynamics simulations. 
Recently, part of our method development efforts focused on machine-learning/data-based approaches. We aim to combine modern machine-learning techniques with a deep understanding of the underlying physics to push the limits of modern simulation and modelling techniques.

_Relevant Publications_: 
- [Assessing the reliability of the dynamics reconstructed from metadynamics M Salvalaglio, P Tiwary, M Parrinello, Journal of chemical theory and computation 10 (4), 1420-1425, 2015.](https://pubs.acs.org/doi/abs/10.1021/ct500040r)
- [Building Maps In Collective Variable Space, I Gimondi, G Tribello, M Salvalaglio, The Journal of Chemical Physics 149 (10), 104104, 2018.](https://pubs.aip.org/aip/jcp/article/149/10/104104/196263)
- [Time-independent free energies from metadynamics via mean force integration, V Marinova, M Salvalaglio, The Journal of Chemical Physics 151 (16), 2019.](https://pubs.aip.org/aip/jcp/article/151/16/164115/1065327)
- [Multiple pathways in NaCl homogeneous crystal nucleation, AR Finney, M Salvalaglio, Faraday Discussions 235, 56-80, 2022.](https://pubs.rsc.org/en/content/articlehtml/2022/fd/d1fd00089f)
- [Machine Learning Nucleation Collective Variables with Graph Neural Networks, FM Dietrich, XR Advincula, G Gobbo, MA Bellucci, M Salvalaglio, Journal of Chemical Theory and Computation, 2023.](https://pubs.acs.org/doi/abs/10.1021/acs.jctc.3c00722)


_Source Code_: 
- [**NNucleate**](https://github.com/mme-ucl/NNucleate) Approximate expensive nucleation collective variables as described in [Dietrich et al. JCTC 2023](https://pubs.acs.org/doi/abs/10.1021/acs.jctc.3c00722). [Documentation + Tutorial](https://flofega.github.io/NNucleate/)
- [**Mean Force Integration**](https://github.com/mme-ucl/MFI) Python implementation of the MFI method, described in [Marinova et al. JPC 2019](https://pubs.aip.org/aip/jcp/article/151/16/164115/1065327).

