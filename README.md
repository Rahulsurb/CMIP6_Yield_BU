# AI-Enabled Climate-Phenology Coupling and Future Productivity Assessment for Semi-Arid Bundelkhand under CMIP6 Forcings
This repository contains the data-processing, climate integration, machine-learning, and future projection framework developed to assess climate-phenology relationships and future agricultural productivity across the semi-arid Bundelkhand region of India. The workflow integrates historical district-level crop-yield observations with seasonal ERA5 climate data to develop AI/ML-based crop-yield models. Multi-model CMIP6 climate projections under SSP2-4.5 and SSP5-8.5 are subsequently evaluated against the historical ERA5 reference during their overlapping period and used as future climate forcing for productivity assessment.
       The framework covers 14 districts of Bundelkhand and incorporates multiple climate dimensions, including precipitation, temperature, relative humidity, radiation, and wind. Five CMIP6 models- ACCESS-CM2, FGOALS-g3, MIROC6, MPI-ESM1-2-HR, and NorESM2-LM are considered under both SSP245 and SSP585 scenarios.

The workflow is organized into three major stages:

#1.Historical modelling: development of crop-yield relationships using historical yield and ERA5 climate data.

#2.CMIP6 evaluation: comparison of CMIP6 simulations with ERA5 during the historical overlap period to assess model behaviour and climate biases.

Future productivity assessment: application of the trained AI/ML yield models to future CMIP6 climate projections for district-level productivity assessment through 2040.

The repository is designed to provide a transparent and reproducible workflow for integrating climate variability, crop productivity, phenological responses, and future climate projections in a semi-arid agricultural environment.
