# EDS220 Fall 2022 Final Project
## Combined NASA Aqua and Terra Satellites Overview -- Fraction of Photosynthetically Active Radiation (FPAR) and Leaf Area Index (LAI)
### Student Authors: Erika Egg, Alessandra Vidal Meza, & Elke Windschitl

## Motivation and Project Goal
The purpose of the notebook is to evaluate whether jungle productivity and area over time have spatially changed in the Lacandon Jungle. The Lacandon Jungle is Maya land and is one of the most biodiverse ecosystems in the world yet it is experiencing significant deforestation due to slash-and-burn farming, logging, and cattle raising (Levinson 2017). From 2000 to 2012, 6 percent of the total forest area was lost, or around 500 million trees and more than 32 million tons of biomass (Soberanes 2018). We use the [MCD15A3H Version 6.1](https://lpdaac.usgs.gov/products/mcd15a3hv061/) data product produced by MODIS instruments on board the National Aeronautics and Space Administration (NASA)'s Terra and Aqua satellites.

MCD15A3H contains data on Fraction of Photosynthetically Active Radiation (FPAR) and Leaf Area Index (LAI). FPAR refers to the fraction of incoming solar radiation (400−700 nm) that is absorbed by the green entities of a plant canopy, and LAI refers to the amount of leaf material in a plant canopy that is estimated as the one-sided green leaf area per unit ground surface area in a broadleaf canopy and as the one−half of the total needle surface area per unit ground area in a coniferous canopy. FPAR is a parameter for modeling ecosystem productivity, and climate and land cover changes (like deforestation) affects FPAR variation (Peng et al. 2012). Similarly, LAI captures changes in tree canopies over time and the potential for gas exchange and light absorption. 

We provide starting parameters and examples for students to replicate this analysis in the Chihuahuan Desert.

Please start with the **finalproject_blank.ipynb** file and check your answers with the **finalproject_demo.ipynb** file.

## Intended Purpose and Important Concepts
The notebook is a learning outcome of the student authors' following skills and knowledge:
- data subsetting
- time series plotting
- period of interest means
- time series mapping


## Packages Utilized
Here we use:
- ee
- geemap
- pandas
- matplotlib


## How to Run
For maximal ease of use, please run this tutorial using the Binder instance below:


[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/EDS220-Fall2022-org/homework-2-team-3/HEAD)


## Questions?
Feel free to reach out to any of us if you have any questions or concerns! Contact information is included in the tutorial notebook.
