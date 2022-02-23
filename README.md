# ESBL-producing E. coli colonization and the gut microbiome and metabolome

This study profiled the gut microbiome using shotgun metagenomics and the gut metabolome using 1H NMR. We profiled the gut metagenome and metabolome of a total of 98 participants, of which half (n = 49) was colonized by an ESBL-producing E. coli and the other half was not as determined by culture and molecular methods. This study was a matched case-control study and participants were matched based on age, sex, having been abroad in the past six months and ethnicity. Matching based on metadata variables is still rare in the microbiome field, but was recently shown to be crucial for avoiding detection of confounding effects in cross-sectional microbiome studies by [Bujkovic-Cvijin et al.](https://www.nature.com/articles/s41586-020-2881-9). Multiple studies have so far shown associations between the gut microbiome and colonization by different multi-drug resistant organisms (MDROs), but these studies were generally conducted in vulnerable patient populations where confounders were omnipresent, see [Ducarmon et al](https://genomemedicine.biomedcentral.com/articles/10.1186/s13073-021-00869-z), [Annavajhala et al.](https://www.nature.com/articles/s41467-019-12633-4) and [le Bastard et al](https://aricjournal.biomedcentral.com/articles/10.1186/s13756-020-00773-y) for examples. Therefore, observed effects in those studies associating gut microbiome features with MDRO colonization cannot be fully disentangled from potential confounding effects. The aim of the present study was to identify a potential role of the gut microbiome in controlling colonization of ESBL-producing E. coli in this matched population.

The paper has been published [here](https://www.biorxiv.org/content/10.1101/2021.05.18.444613v1).
If you need the raw sequence data to analyze the data yourself, you can find all raw sequence data under PRJEB36316.
The participant numbers [e.g. P01,P02 etc.] listed under this project number can be matched with the metadata file that is available under Data/Metadata.

## Requirements
- R version 4.0.4 (2021-02-15) -- "Lost Library Book".
- All packages and dependencies loaded in the different markdown scripts. 

## Worfklow
- Clone the Github page
- To ease reproducing our results, I have saved the necessary files as .rds files, so that these can be loaded in immediately. It is important that you first run the 'Scripts/Data_Prep_Cleaning.Rmd' file, which loads all necessary input, after which you should be able to load all other .Rmd.
- Note that figures can be reproduced on content, but the exact design of the figures cannot be reproduced, as this is done in-house by the respective journal

## Contact
In case you have any questions about the code/analyses/availability of materials, or would require more information in any other way, you can contact me, [Quinten Ducarmon](mailto:q.r.ducarmon@lumc.nl)! 