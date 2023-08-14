# TRhizo-localAdaptation

Data, metadata, and R code for “Mosaic of local adaptation between white clover and rhizobia along an urbanization gradient”
================
David Murray-Stoker
23 January 2021

Data, metadata, and all R code for reproducing analyses for the manuscript:

Murray-Stoker, D., and M. T. J. Johnson. Ecological consequences of urbanization on a legume-rhizobia mutualism.

[![DOI](https://zenodo.org/badge/332053459.svg)](https://zenodo.org/badge/latestdoi/332053459)


## Abstract

Urbanization alters many biotic and abiotic environmental factors, but the effects of urbanization on local adaptation and coevolution between species remains largely unstudied. Using a common garden experiment of 30 populations and 1080 plants, we tested for local adaptation in the mutualism between white clover (*Trifolium repens*) and rhizobia (*Rhizobium leguminosarum* symbiovar *trifolii*) along an urbanization gradient. Our results show a spatial mosaic in local adaptation, with stronger local adaptation for rhizobia than white clover. While nitrogen addition (N) strongly influenced plant biomass and nodule density, it did not consistently mediate patterns of local adaptation. The strength of local adaptation was positively related between white clover and rhizobia under N addition, suggesting that soil N mediates coadaptation between white clover and rhizobia. Local adaptation was not influenced by urbanization, indicating that while urbanization does influence the ecology of plant-microbe interactions, it does not disrupt local adaptation and coevolution among mutualists.


## Contents

The [R Project](https://github.com/dmurraystoker/TRhizo-localAdaptation/blob/main/TRhizo-localAdaptation.Rproj) provides a local relative directory for all data and R code.


### Data

All data and R objects are provided in the [data](https://github.com/dmurraystoker/TRhizo-localAdaptation/tree/main/data) folder, with raw data in .xlsx files in the [raw_data](https://github.com/dmurraystoker/TRhizo-localAdaptation/tree/main/raw_data) folder.

There are 5 primary data files from which all analyses and downstream variables were calculated:

* localAdaptation-experiment_data-biomass.csv
  - Aboveground and belowground biomass data
* localAdaptation-experiment_data-nodules.csv
  - Nodule density and fixing nodule density data
* localAdaptation-site_information.csv
  - Latitude and longitude for each site
* localAdaptation-microbiome_data-root.csv
  - Sample identifier data and fitness responses for root samples
* localAdaptation-microbiome_data-soil.csv
  - Sample identifier data for soil microbiome inoculant samples.

Metadata associated with these files and the `raw_data` equivalents is provided [here](link.md).


### Sequences

All raw sequence files are provided on NCBI at [BioProject Number](link).


### Data Analysis

R Markdown code for all data analyses and figure creation are provided in the [data_analysis](https://github.com/dmurraystoker/TRhizo-localAdaptation/tree/main/data_analysis) folder. Separate README files are provided for each subfolder to describe what the purpose of the script files.


### Using this repository

To use the data and R code for this project:

1. `git clone` this repository or download it as a zip folder
2. Open `R Studio`, go to `file > Open project`, and open the `TRhizo-localAdaptation.Rproj`
R Project associated with this repository.
3. The analyses can be performed by running through the code in [data_analysis](https://github.com/dmurraystoker/TRhizo-localAdaptation/tree/main/data_analysis).

