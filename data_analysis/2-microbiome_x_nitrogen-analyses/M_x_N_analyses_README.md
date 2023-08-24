# TRhizo-localAdaptation


README for the M x N analyses
================
David Murray-Stoker

14 August 2023



## Workflow

Code files to conduct the linear mixed-effects models following the model fitting and selection procedure. There are 4 files in this folder that conduct the analyses, with slight differences in approach.

`microbiome_x_nitrogen-analyses.Rmd` = primary analysis script with results presented in the manuscript.

`microbiome_x_nitrogen-analyses-alternate.Rmd` = additional analysis to compare and contrast the interpretation of results when aboveground biomass was fitted using a different model structure. There were no differences in ecological interpretation with the results from `microbiome_x_nitrogen-analyses.Rmd`, so we only focused on those results.

`microbiome_x_nitrogen-global_analyses.Rmd` = identical analyses to `microbiome_x_nitrogen-analyses.Rmd`, except microbiome was re-coded as Local and Nonlocal~Global~ (i.e., 2 levels instead of 3). Results were presented in the supplement and showed similar patterns to the primary analyses.

`microbiome_x_nitrogen-global_analyses-alternate.Rmd` = additional analysis to examine how re-coding microbiome to 2 levels and fitting aboveground biomass to a different model structure could affect the results. There were only minor differences in statistical results and no differences in ecological interpretation, so we only focused on the results from the primary analysis.


Each code file has it own workspace for reproducibility.
