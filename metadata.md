Metadata for "Mosaic of local adaptation between white clover and rhizobia along an urbanization gradient"
================
David Murray-Stoker

# TRhizo-localAdaptation


Metadata associated with the manuscript:

Murray-Stoker, D. and M. T. J. Johnson. Mosaic of local adaptation between white clover and rhizobia along an urbanization gradient.

# Metadata


## Raw Data


### file = TRhizo-localAdaptation-experiment\_data.xlsx

**Biomass** Sheet = aboveground and belowground biomass data

| Variable   | Description                                             | Type      | 
|:-----------|:--------------------------------------------------------|:----------|
| UID | Unique sample identifier | Integer |
| Block | Block to which the sample was assigned | Integer |
| Row | Row to which the sample was assigned, range = 1-6 | Integer |
| Pot | Column to which the sample was assigned, range = 1-20 | Integer |
| Population | Source population for the sample | Character |
| Microbiome | Microbiome treatment assigned to the sample, levels = Local, Nonlocal\_R, and Nonlocal\_U | Character |
| Nitrogen | Nitrogen treatment assigned to the sample, levels = Ambient\_N, and N\_Addition | Character |
| Replicate | Replicate for the population-microbiome-nitrogen treatment combination, range = 1-6 | Integer |
| Aboveground\_Biomass | Total aboveground biomass (g), measured to 0.0001 | Numeric |
| Belowground\_Biomass | Total belowground biomass (g), measured to 0.0001 | Numeric |


**Nodules** Sheet = total nodule and fixing nodule data

| Variable   | Description                                             | Type      | 
|:-----------|:--------------------------------------------------------|:----------|
| UID | Unique sample identifier | Integer |
| Block | Block to which the sample was assigned | Integer |
| Row | Row to which the sample was assigned, range = 1-6 | Integer |
| Pot | Column to which the sample was assigned, range = 1-20 | Integer |
| Population | Source population for the sample | Character |
| Microbiome | Microbiome treatment assigned to the sample, levels = Local, Nonlocal\_R, and Nonlocal\_U | Character |
| Nitrogen | Nitrogen treatment assigned to the sample, levels = Ambient\_N, and N\_Addition | Character |
| Replicate | Replicate for the population-microbiome-nitrogen treatment combination, range = 1-6 | Integer |
| Root\_1\_Length | Length of the first measured root (cm), measured to the nearest 0.1 cm | Numeric |
| Root\_2\_Length	| Length of the second measured root (cm), measured to the nearest 0.1 cm | Numeric |
| Root\_3\_Length	| Length of the third measured root (cm), measured to the nearest 0.1 cm | Numeric |
| Root\_1\_Total_Nodules | Total number of nodules on the first measured root (count) | Integer |
| Root\_2\_Total_Nodules | Total number of nodules on the second measured root (count) | Integer |
| Root\_3\_Total_Nodules | Total number of nodules on the third measured root (count) | Integer |
| Root\_1\_Fixing_Nodules	| Total number of fixing nodules on the first measured root (count) | Integer |
| Root\_2\_Fixing_Nodules	| Total number of fixing nodules on the second measured root (count) | Integer |
| Root\_3\_Fixing_Nodules	| Total number of fixing nodules on the third measured root (count) | Integer |
| Total\_Root\_Length	| Sum of the root length for all measured roots (cm) | Numeric |
| Total\_Nodules	| Sum of the total number of nodules (fixing \& non-fixing) | Integer |
| Total\_Fixing\_Nodules | Sum of the total number of fixing nodules | Integer |
| Nodule\_Density | Total number of nodules standardized by root length, Total\_Nodules / Total\_Root\_Length | Numeric |
| Percent\_Fixing\_Nodules | Percentage of nodules that were fixing (%) | Numeric |
| Fixing\_Nodule\_Density | Total number of fixing nodules standardized by root length, Total\_Fixing\_Nodules / Total\_Root\_Length | Numeric |


**Sample Processing** sheet = progress tracker during sample processing

Sheet with customized cells (with embedded calculations) to track how many samples were processed. Cells automatically filled as samples were processed.



### file = TRhizo-localAdaptation-site\_information.xlsx

| Variable   | Description                                             | Type      | 
|:-----------|:--------------------------------------------------------|:----------|
| Population | Population to which the information corresponds | Character |
| Latitude | Latitude (decimal degrees) of the population along the urbanization gradient | Character | 
| Longitude | Longitude (decimal degrees) of the population along the urbanization gradient | Character |
| Community\_Type | Soil community type associated with that populations, levels = Inoculant (paired with a local population), Rural (part of the Nonlocal\_R inoculant), or Urban (Part of the Nonlocal\_U inoculant) | Character |



### file = cockerham\_data\_cleaned.xlsx

Formatted data for Cockerham's test, with this cleaned file formatted from results exported during the data analysis.

| Variable   | Description                                             | Type      | 
|:-----------|:--------------------------------------------------------|:----------|
| Trait | Fitness trait under consideration; aboveground biomass, nodule density, and fixing nodule density | Character |
| Env1\_Env2 | Environmental comparison to which the data correspond; Env1 is first, Env2 is second | Character |
| Vg1 | Genetic variance associated with the trait in environment 1 | Numeric |
| Vg2 | Genetic variance associated with the trait in environment 2 | Numeric |
| Rg | Genetic correlation between the two environments | Numeric |



### file = cockerham\_data\_cleaned-alternate.xlsx

Formatted data for Cockerham's test, with this cleaned file formatted from results exported during the data analysis. This table is identical to the previous table, except a different linear mixed-effects model was used for aboveground biomass.

| Variable   | Description                                             | Type      | 
|:-----------|:--------------------------------------------------------|:----------|
| Trait | Fitness trait under consideration; aboveground biomass, nodule density, and fixing nodule density | Character |
| Env1\_Env2 | Environmental comparison to which the data correspond; Env1 is first, Env2 is second | Character |
| Vg1 | Genetic variance associated with the trait in environment 1 | Numeric |
| Vg2 | Genetic variance associated with the trait in environment 2 | Numeric |
| Rg | Genetic correlation between the two environments | Numeric |



### file = TRhizo-localAdaptation-microbiome\_data.xlsx

**Root** Sheet = sample identifier and fitness variable associated with root samples that were sequenced

| Variable   | Description                                             | Type      | 
|:-----------|:--------------------------------------------------------|:----------|
| Sequence\_ID | Unique sequence ID associated with the sample; corresponds to the fasta file | Character |
| UID | Unique sample identifier; consistent across datasheets | Integer |
| Population | Source population for the sample | Character |
| Microbiome | Microbiome treatment assigned to the sample, levels = Local, Nonlocal\_R, and Nonlocal\_U | Character |
| Nitrogen | Nitrogen treatment assigned to the sample, levels = Ambient\_N, and N\_Addition | Character |
| Aboveground\_Biomass | Total aboveground biomass (g), measured to 0.0001 | Numeric |
| Belowground\_Biomass | Total belowground biomass (g), measured to 0.0001 | Numeric |
| Nodule\_Density | Total number of nodules standardized by root length, Total\_Nodules / Total\_Root\_Length | Numeric |
| Fixing\_Nodule\_Density | Total number of fixing nodules standardized by root length, Total\_Fixing\_Nodules / Total\_Root\_Length | Numeric |


**Soil** Sheet = sample identifier and fitness variable associated with root samples that were sequenced

| Variable   | Description                                             | Type      | 
|:-----------|:--------------------------------------------------------|:----------|
| Sequence\_ID | Unique sequence ID associated with the sample; corresponds to the fasta file | Character |
| Population | Source population for the sample | Character |
| Inoculant\_Type | Soil community type associated with that populations, levels = Local (paired with a local population), Rural (part of the Nonlocal\_R inoculant), Urban (Part of the Nonlocal\_U inoculant), Ambient\_N (control pot), and N\_Addition (control pot) | Character |



### file = TRhizo-localAdaptation-carbon\_nitrogen\_data.xlsx

Soil carbon and nitrogen data (total and isotopes) from the control pots in the experiment.

| Variable   | Description                                             | Type      | 
|:-----------|:--------------------------------------------------------|:----------|
| Sample\_ID | Treatment control and replicate represented by the pot | Character |
| Sample\_Weight | Mass of the sample submitted for analysis (mg) | Numeric |
| Total\_Carbon | Total amount of carbon in the sample (%) | Numeric |
| Delta\_13C | Carbon isotope of the sample in delta notation, ratio C^13^ / C^12^ | Numeric |
| Total\_Nitrogen | Total amount of nitrogen  in the sample (%) | Numeric |
| Delta\_15N | Nitrogen isotope of the sample in delta notation, ratio N^15^ / N^14^ | Numeric |






## Cleaned Data


### file = localAdaptation-experiment\_data-biomass.csv

| Variable   | Description                                             | Type      | 
|:-----------|:--------------------------------------------------------|:----------|
| UID | Unique sample identifier | Integer |
| Block | Block to which the sample was assigned | Integer |
| Row | Row to which the sample was assigned, range = 1-6 | Integer |
| Pot | Column to which the sample was assigned, range = 1-20 | Integer |
| Population | Source population for the sample | Character |
| Microbiome | Microbiome treatment assigned to the sample, levels = Local, Nonlocal\_R, and Nonlocal\_U | Character |
| Nitrogen | Nitrogen treatment assigned to the sample, levels = Ambient\_N, and N\_Addition | Character |
| Replicate | Replicate for the population-microbiome-nitrogen treatment combination, range = 1-6 | Integer |
| Aboveground\_Biomass | Total aboveground biomass (g), measured to 0.0001 | Numeric |
| Belowground\_Biomass | Total belowground biomass (g), measured to 0.0001 | Numeric |



### file = localAdaptation-experiment\_data-nodules.csv

| Variable   | Description                                             | Type      | 
|:-----------|:--------------------------------------------------------|:----------|
| UID | Unique sample identifier | Integer |
| Block | Block to which the sample was assigned | Integer |
| Row | Row to which the sample was assigned, range = 1-6 | Integer |
| Pot | Column to which the sample was assigned, range = 1-20 | Integer |
| Population | Source population for the sample | Character |
| Microbiome | Microbiome treatment assigned to the sample, levels = Local, Nonlocal\_R, and Nonlocal\_U | Character |
| Nitrogen | Nitrogen treatment assigned to the sample, levels = Ambient\_N, and N\_Addition | Character |
| Replicate | Replicate for the population-microbiome-nitrogen treatment combination, range = 1-6 | Integer |
| Total\_Root\_Length	| Sum of the root length for all measured roots (cm) | Numeric |
| Total\_Nodules	| Sum of the total number of nodules (fixing \& non-fixing) | Integer |
| Total\_Fixing\_Nodules | Sum of the total number of fixing nodules | Integer |
| Nodule\_Density | Total number of nodules standardized by root length, Total\_Nodules / Total\_Root\_Length | Numeric |
| Percent\_Fixing\_Nodules | Percentage of nodules that were fixing (%) | Numeric |
| Fixing\_Nodule\_Density | Total number of fixing nodules standardized by root length, Total\_Fixing\_Nodules / Total\_Root\_Length | Numeric |



### file = localAdaptation-site\_information.csv

| Variable   | Description                                             | Type      | 
|:-----------|:--------------------------------------------------------|:----------|
| Population | Population to which the information corresponds | Character |
| Latitude | Latitude (decimal degrees) of the population along the urbanization gradient | Character | 
| Longitude | Longitude (decimal degrees) of the population along the urbanization gradient | Character |
| Community\_Type | Soil community type associated with that populations, levels = Inoculant (paired with a local population), Rural (part of the Nonlocal\_R inoculant), or Urban (Part of the Nonlocal\_U inoculant) | Character |
  


### file = localAdaptation-microbiome\_data-root.csv

| Variable   | Description                                             | Type      | 
|:-----------|:--------------------------------------------------------|:----------|
| Sequence\_ID | Unique sequence ID associated with the sample; corresponds to the fasta file | Character |
| UID | Unique sample identifier; consistent across datasheets | Integer |
| Population | Source population for the sample | Character |
| Microbiome | Microbiome treatment assigned to the sample, levels = Local, Nonlocal\_R, and Nonlocal\_U | Character |
| Nitrogen | Nitrogen treatment assigned to the sample, levels = Ambient\_N, and N\_Addition | Character |
| Aboveground\_Biomass | Total aboveground biomass (g), measured to 0.0001 | Numeric |
| Belowground\_Biomass | Total belowground biomass (g), measured to 0.0001 | Numeric |
| Nodule\_Density | Total number of nodules standardized by root length, Total\_Nodules / Total\_Root\_Length | Numeric |
| Fixing\_Nodule\_Density | Total number of fixing nodules standardized by root length, Total\_Fixing\_Nodules / Total\_Root\_Length | Numeric |



### file = localAdaptation-microbiome\_data-soil.csv

| Variable   | Description                                             | Type      | 
|:-----------|:--------------------------------------------------------|:----------|
| Sequence\_ID | Unique sequence ID associated with the sample; corresponds to the fasta file | Character |
| Population | Source population for the sample | Character |
| Inoculant\_Type | Soil community type associated with that populations, levels = Local (paired with a local population), Rural (part of the Nonlocal\_R inoculant), Urban (Part of the Nonlocal\_U inoculant), Ambient\_N (control pot), and N\_Addition (control pot) | Character |




