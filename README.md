[![DOI](https://zenodo.org/badge/727367017.svg)](https://zenodo.org/doi/10.5281/zenodo.10403744)

# Grassland Phenology Final Project
Repository for Earth Analytics Fall 2023 Grassland Phenology final project, "Using remotely-sensed NDVI to understand temporal and spatial patterns of grassland brown-down in Boulder County, Colorado."

## Contact
Advyth Ramachandran (advyth.ramachandran@colorado.edu)

PhD Student, Department of Ecology & Evolutionary Biology, University of Colorado, Boulder

## Project overview

This project was conducted as my Final Project for the Earth Analytics Bootcamp Fall 2023 course at the University of Colorado, Boulder. In this project, I aimed to analyze vegetation phenology (specifically, brown-down) from MODIS NDVI data and understand heterogeneity in phenology across grassland community types in Boulder County. Please see the notebook for a full project description.


## How to run the code

This code was developed in the Earth Analytics Development Environment which can be installed using the instructions found at this GitHub repository: https://github.com/earthlab/earth-analytics-python-env (DOI: 10.5281/zenodo.1311239). The notebook file requires Jupyter Notebook to run.

There is only one notebook file for this project and cells must be run in order.

## Acknowledgements

I thank Elsa Culler for extensive technical assistance and Katharine Suding for input on project planning.

## Grading Rubric

Modified from the Final Assignment rubric to match the work proposed in this final project. Modifications indicated in _italics_.


|**Description**|**Maximum Points**|
|:----|:----|
|**GITHUB REPOSITORY**|30|
|Project is stored on GitHub|3|
|The repository has a README that introduces the project|5|
|The README also explains how to run the code|5|
|The README has a DOI badge at the top|5|
|The repository has a LICENSE|2|
|Repository is organized and there are not multiple versions of the same file in the repository|5|
|Repository files have machine and human-readable names|5|
|**CODE**|120|
|The code runs all the way through using the instructions from the README|10|
|The code follows the PEP-8 style standard|10|
|The code is well-documented with comments|10|
|The code uses functions and/or loops to be DRY and modular|10|
|Any functions have numpy-style docstrings|10|
|The code makes use of conditionals to cache data and/or computations, making efficient use of computing resources|10|
|The code contains a site map for the _vegetation community type data_|10|
|The code downloads the _NDVI raster layer for each timestep_|10|
|The code correctly _calculates the brown-down 10th percentile thresholds for each year_|10|
|The code harmonizes the _polygon/vector and raster data_|10|
|For _each year and vegetation polygon, the brown-down date is calculated as a zonal mean of the brown-down date raster_|10|
|The code produces at least one (sub)figure displaying the results|10|
|Any unfinished components have detailed pseudocode or a flow diagram explaining how they could be finished in the future, and or a complete bug report explaining the problem|up to 90 points, in place of other categories|
|**WRITTEN ANALYSIS**|50|
|The notebook contains a project description|10|
|The notebook contains a researched site description|10|
|The notebook contains a data description and citation for each data source|10|
|The notebook contains a description of _how brown-down was calculated_|10|
|The notebook contains a headline and description for each figure|10|
