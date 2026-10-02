# Zeng2026
Code used in [Zeng et al 2026](https://www.biorxiv.org/content/10.64898/2026.08.28.747564v1) **The mTOR pathway drives daily physiology** 

Analysis of proteomic and phosphoproteomic timecourse data from mouse fibroblasts, liver, brain. 

## Directory structure:
Brain: proteomics and phosphoproteomics for Fig 5 
Liver: proteomics and phosphoproteomics for Fig 4
Fibroblast INK128 peak trough: proteomics and phosphoproteomics for Fig 1
Fibroblast_timecourse_phosphoproteomics: phosphoproteomics for Fig 1 

Each folder contains:
.txt files with output from Perseus
.Rmd notebooks with analysis 
.csv or .pdf output from analyses 

Notebooks must be run in the indicated order within folders but order of running each folder does not matter.

## Dependencies for R markdown notebooks:

### CRAN:
tidyr
dplyr
tibble
ggplot2
ggrepel
purrr
psych

### Bioconductor:
edgeR
RAIN



