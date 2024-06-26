# Data and Code Repository for Original Research Article Titled: "Coverage and Facet Dependent Multiscale Modeling of O* and H* Adsorption on Pt Catalytic Nanoparticles"
The original research article is by Ayodeji Omoniyi* and Alyssa J.R. Hensley*, and is published in _The Journal of Physical Chemistry C_ (DOI: 10.1021/acs.jpcc.3c08335).

*Department of Chemical Engineering and Materials Science at Stevens Insitute of Technology

## Article Abstract
Within computational heterogeneous catalysis, two critical factors exist─coverage and multifaceted effects─which are challenging to incorporate and contribute to differences between the results obtained from computational and experimental studies. Such disparities exist when significant adsorbate–adsorbate interactions are present, particularly when coupled with computationally limited facet sampling. Here, we designed a study to demonstrate the significance of coverage and facet effects on the predicted coverages for O* and H* on Pt nanoparticles. This is accomplished by employing multiscale modeling techniques using a three-pronged approach consisting of density functional theory (DFT), ab initio phase diagrams, and mean-field microkinetic models. Overall, adsorbate–adsorbate interactions are repulsive and far stronger for O*/Pt than for H*/Pt. For O* on Pt(111), repulsive interactions are both two- and three-body, but on Pt(100) and Pt(110), they are predominantly three-body. Through benchmarks to existing experimental literature, we demonstrate that experimentally observed coverages and desorption temperatures can be accurately estimated by computational models when the adsorbate–adsorbate interactions are included. Finally, by combining microkinetic models at the equilibrium limit with kubic harmonic interpolation, we model the impacts of the treatment of adsorbate–adsorbate interactions on the predicted O* and H* coverages over multifaceted Pt nanoparticles. Omitting adsorbate–adsorbate interactions over Pt nanoparticles leads to an overestimation of equilibrium coverages of the adsorbates (maximum of 0.29 and 0.11 ML for O* and H*, respectively) across a wide range of temperatures and pressures relevant to heterogeneous catalysis. Altogether, our work demonstrates that the inclusion of coverage and facet effects increases the accuracy of computational models for heterogeneous catalysts.

## Content
- Raw data for ground state DFT calculations in JSON format.
- Post-processed vibrational frequencies, calculated within the harmonic oscillator approximation, in TXT format.
- Jupyter Notebooks for:
  - Multi-variable regression of surface vibrational Gibbs free energy as a function of adsorbate coverage and temperature.
  - Ab initio phase diagrams.
  - Adsorbate coverage over multi-faceted nanoparticles as a function of temperature and pressure determined via combination of kubic harmonic interpolation and mean-field models. 

## Contribution Statement
Contributions to this project were determined using CRediT (Contributor Roles Taxonomy). Here is the contribution statement:
- A.O. contributed to data curation, formal analysis, investigation, methodology, visualization, and writing (original draft).
- A.J.R.H. contributed to conceptualization, funding acquisition, methodology, project administration, supervision, and writing (original draft).
