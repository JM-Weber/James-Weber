---
layout: default
---

# My Work with UKESM

[Back to Home](./)

### Overview
The United Kingdom Earth System Model ([UKESM](https://ukesm.ac.uk)) is a global chemistry-climate model which simulates all aspects of the Earth System including the atmosphere, the land surface, the ocean and the cryosphere and the interactions between these components. UKESM was one of the major climate models which contributed to the 6<sup>th</sup> Coupled Model Intercomparison project (CMIP6) which contributed to the evidence base of the IPCC 6<sup>th</sup> Assessment Report in 2021 (AR6). A detailed description of UKESM can be found [here](https://agupubs.onlinelibrary.wiley.com/doi/full/10.1029/2019MS001739). 

### My Experience with UKESM

I have extensive experience setting up and running simulations in UKESM for my own work and for colleagues. My experience includes:

- Free-running atmosphere-only experiments such as those in AerChemMIP ([Collins et al; 2017](https://gmd.copernicus.org/articles/10/585/2017/)). <br /> 
- Emission perturbation experiments 
  - doubling BVOC emissions 
  - scaling emissions of particular species 
  - creating timeseries and timeslice emission files from different future scenarios like SSP126 and SSP370).
- Land use/cover change experiments. This has involved modifying land surface input files in UKESM's atmosphere-only mode (e.g. increasing or decreasing forest cover) including converting and regridding land surface input files from CESM to work in UKESM.<br /> 
- Fully coupled simulations (all components of UKESM free to interact).  <br /> 
- Nudged atmosphere-only experiments with high frequency output for comparison against surface, aircraft and satellite observations.<br /> 
- Changing the chemical and aerosol processes simulated by the model and assessing the impact (e.g. [Weber et al., 2021](https://gmd.copernicus.org/articles/14/5239/2021/)). 

I have also acted as a demonstrator for the 2021 and 2022 UKCA training courses (link [here](https://www.ukca.ac.uk/wiki/index.php/UKCA_Chemistry_and_Aerosol_Tutorials_at_vn11.8)) run by Dr N. Luke Abraham. UKCA (United Kingdom Chemistry and Aerosol) is the component of UKESM which simulates atmospheric chemistry and aerosol processes. This demonstrating role involved helping students with the course's exercises and explaining aspects of the model.  


### My contributions to UKESM
Model development is an ongoing process informed by advances in the understanding of important Earth system processes, for example the chemical reactions of major BVOCs. I view model development as the responsibility of all researchers who use the model and I have been fortunate to collaborate with colleagues at the Met Office and the Universities of Leeds and Cambridge to make some improvements to UKESM such that I am now a co-author on the technical documentation (link [here](https://code.metoffice.gov.uk/doc/um/latest/papers/umdp_084.pdf) - requires MOSRS access).

#### CRI-Strat 2
As an atmospheric chemist I am primarily interested in processes which determine atmospheric composition. These are simulated in UKCA. During my PhD I led work to add and evaluate an improved chemistry mechanism called CRI-Strat 2 (CS2) in UKCA which features some of the most recent advances in the understanding of isoprene oxidation chemistry with knock-on effects for oxidant concentrations and aerosol (paper [here](https://gmd.copernicus.org/articles/14/5239/2021/)). CS2 is now a selectable option in UKESM. 

#### Secondary Organic Aerosol from Isoprene
During my PhD I improved the coupling between BVOCs and aerosol by updating the aerosol code in UKESM to allow for production of secondary organic aerosol (SOA) from isoprene in addition to its default production from monoterpenes. This significantly improves the faithfulness of SOA production, particularly in its spatial variation given that monoterpenes are emitted to a greater extent by mid and high latitude forests while isoprene emissions occurs to a much greater extent in the tropics. Working with Dr Colin Johnson at the Met Office, SOA production from isoprene will be a selectable option in UKESM from vn12.3. 


#### Isoprene and Monoterpenes Emission Factors 
UKESM simulates isoprene and monoterpene emissions interactively, combining parameteristions for the effect of temperature, CO<sub>2</sub> concentration, photosynthetic activity and the propensity of different types of  vegetation (grasses, evergreen trees, deciduous trees etc.) to emit these species. The latter is described by each type of vegetation's emission factor and I am currently working on developing a new set of emission factors which will improve the simulation of BVOC emissions. This will be particularly important for modelling future climate scenarios as changes to the land use and land cover (e.g. deforesation for agriculuture or afforestation to remove CO,sub>2</sub>) are likely to have significant impacts on BVOC emissions.

