# TRhizo-localAdaptation


README for the model fitting and selection procedure
================
David Murray-Stoker
14 August 2023



## Workflow

There are 2 script files: `microbiome_x_nitrogen-model_fitting.Rmd` and `microbiome_x_nitrogen-global_model_fitting.Rmd`.
Both files are essentially identical, except the `microbiome_x_nitrogen-model_fitting.Rmd` used all 3 microbiome treatments (Local, Nonlocal~Rural~, and Nonlocal~Urban~) and `microbiome_x_nitrogen-global_model_fitting.Rmd` only used 3 microbiome treatments (Locan and Nonlocal~Global~; Nonlocal~Rural~ and Nonlocal~Urban~ were both re-coded as Nonlocal~Global~).

Both scripts conduct the model fitting and selection procedure, and each has its own workspace for reproducibility.