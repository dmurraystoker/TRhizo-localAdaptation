# TRhizo-localAdaptation


README for the model fitting and selection procedure
================
David Murray-Stoker
14 August 2023



## Workflow

There are 2 script files: `microbiome_x_nitrogen-model_fitting.Rmd` and `microbiome_x_nitrogen-global_model_fitting.Rmd`.
Both files are essentially identical, except the `microbiome_x_nitrogen-model_fitting.Rmd` used all 3 microbiome treatments (Local, Nonlocal<sub>Rural</sub>, and Nonlocal<sub>Urban</sub>) and `microbiome_x_nitrogen-global_model_fitting.Rmd` only used 3 microbiome treatments (Locan and Nonlocal<sub>Global</sub>; Nonlocal<sub>Rural</sub> and Nonlocal<sub>Urban</sub> were both re-coded as Nonlocal<sub>Global</sub>).

Both scripts conduct the model fitting and selection procedure, and each has its own workspace for reproducibility.
