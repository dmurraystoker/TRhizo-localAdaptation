# TRhizo-localAdaptation


README for local adaptation-by-urbanization analyses
================
David Murray-Stoker
14 August 2023



## Workflow


First you should run the `urbanization_metrics.Rmd` file to calculate urbanization metrics from raster files.

Second, running the code in `local_adaptation_by_urbanization.Rmd` will perform each linear regression to examine the relationship between local adaptation and urbanization.

To run `urbanization_metrics.Rmd`, you will need to download the relevant raster files and check the directory to make sure you are telling R to look for the rasters in the correct folder.