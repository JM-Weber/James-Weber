---
layout: default
---

# My Work with UKESM

[Back to Home](./)

### Overview
The United Kingdom Earth System Model (UKESM) is a global chemistry-climate model. UKESM simulates all aspects of the Earth System including the atmosphere, the land surface, the ocean and the cryosphere and the interactions between these components. UKESM was one of the major climate models which contributed to the 6<sup>th</sup> Coupled Model Intercomparison project (CMIP6) which contrinbuted to the evidence base of the IPCC 6<sup>th</sup> Assessment Report in 2021 (AR6). A detailed description of UKESM can be found [here](https://agupubs.onlinelibrary.wiley.com/doi/full/10.1029/2019MS001739). 

### My Experience with UKESM

I have extensive experience setting up and running simulations in UKESM. My experience includes:

- Free-running atmosphere-only experiments such as those in AerChemMIP ([Collins et al; 2017](https://gmd.copernicus.org/articles/10/585/2017/)). 
- Modifying land surface input files in atmosphere-only mode (e.g. increasing forest cover), including converting and regridding land surface input files from a different climate model (CESM) to work in UKESM.
- Emission perturbation experimenst (e.g. doubling BVOC emissions, creating timeseries and timeslice emission files from different future scenarioes like ssp126 and ssp370).
- Fully coupled simulations (all components of UKESM free to interact).  
- Nudged atmosphere-only experiments with high frequency output for comparison against surface, aircraft and satellite observations.
- Changing the chemical reactions simulated by the model and assessing the impact ([Weber et al., 2021](https://gmd.copernicus.org/articles/14/5239/2021/)). 

I have also acted as a demonstrator for the 2021 and 2022 UKCA training courses (link [here](https://www.ukca.ac.uk/wiki/index.php/UKCA_Chemistry_and_Aerosol_Tutorials_at_vn11.8)) run by Dr N. Luke Abraham.The involved helping students with the course exercises and explaining aspects of the model.  


### My contributions to UKESM

#### CRI-Strat 2
As an atmospheric chemist I am primarily interested in processes which determine atmospheric composition. These are simulated in the United Kingdom Chemistry and Aerosols (UKCA) module of UKESM. During my PhD I led work to add and evaluate an improved chemistry mechanism called CRI-Strat 2 (CS2) in UKCA which features some of the most recent updates to isoprene chemistry with knock-on effects for oxidant concentrations and aerosol (paper [here](https://gmd.copernicus.org/articles/14/5239/2021/)). CS2 is now a selectable option in UKESM. 

#### Secondary Organic Aerosol from Isoprene
During my PhD I improved the coupling between BVOCs and aerosol by updating the aerosol code in UKESM to allow for production of secondary organic aerosol (SOA) from isoprene in addition to its default production from monoterpenes. This significantly improves the faithfulness of SOA production, particularly in its spatial variation given that monoterpenes are emitted to a greater extent by mid and high latitude forests while isoprene emissions occurs to a much greater extent in the tropics.

#### Isoprene and Monoterpenes Emission Factors 
UKESM simulates isoprene and monoterpene emissions interactively, combining temperature, CO<sub>2</sub> concentrations, photosynthetic activity and the propensity of different types of  vegetation (grasses, evergreen trees, deciduous trees etc.) to emit these species. The latter is described by the vegetation's emission factor and I am currently working on developing a new set of emission factors which will improve the simulation of BVOC emission. This will be particularly important for modelling future climate scenarios as changes to the land use and land cover (e.g. deforesation for agriculuture) are likely to have significant impacts on BVOC emissions.
