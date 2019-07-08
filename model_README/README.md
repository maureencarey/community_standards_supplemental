# README for generating iPfal19

## summary 

This model is the third iteration of the *Plasmodium falciparum* 3D7 genome-scale metabolic network reconstruction, curated by Maureen Carey and collaborators. The original reconstruction (DOI: 10.1038/msb.2010.60) was generated using a custom pipeline. All documentation here is in regard to curation conducted since the original publication.

## genome

not provided by the original publication

Nomenclature has been kept up-to-date with PlasmoDB's *Plasmodium falciparum* 3D7 genome (release 44 as of July 8th, 2019). Given the lack of experimental data availability, we integrated data from strains other than 3D7 as well.

## database

not provided by the original publication

Modifications have been consistent with the BiGG namespace (DOI: 10.1093/nar/gkv1049), whenever possible.

## software

no provided by the original publication

### round 1: manual curation published in 

See code here: https://github.com/gulermalaria/iPfal17/model_curation_careyBMCG.m

This code uses MATLAB R2013b, COBRA Toolbox 2015, and Gurobi 5.

### round 2: manual curation published in 

Original code not publically available; modifications were documented in the manuscript's Additional File 1:Table S1 and recreated in round 3 curation.

### round 3: manual curation

See code here: https://github.com/maureencarey/paradigm/blob/master/model_refinement/step_2_curate_iPfal17.py

This code uses python 3.6.6 and cobrapy 0.14.1.
