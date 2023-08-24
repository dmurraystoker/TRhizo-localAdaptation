# TRhizo-localAdaptation


README for Cockerham's test
================
David Murray-Stoker

14 August 2023



## Workflow

Code files to conduct Cockerham's test. Similar to the M x N analyses, there are 4 separate code files in the folder to conduct the analyses with minor differences in approach.

`cockerhams_test.Rmd` = primary analysis script with results presented in the manuscript.

`cockerhams_test-alternate.Rmd` = additional analysis to compare and contrast the interpretation of results when aboveground biomass was fitted using a different model structure. There were no differences in ecological interpretation with the results from `microbiome_x_nitrogen-analyses.Rmd`, so we only focused on those results.

`cockerhams_test-global.Rmd` = identical analyses to `cockerhams_test.Rmd`, except microbiome was re-coded as Local and Nonlocal<sub>Global</sub> (i.e., 2 levels instead of 3). 

`cockerhams_test-global_alternate.Rmd` = additional analysis to examine how re-coding microbiome to 2 levels and fitting aboveground biomass to a different model structure could affect the results. There were only minor differences in statistical results and no differences in ecological interpretation, so we only focused on the results from the primary analysis.


Each code file has it own workspace for reproducibility.
