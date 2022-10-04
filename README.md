# Photosynthetic-carbon-uptake-correlates-with-cell-protein-content-during-lipid-accumulation-in-the-m
R script associated to the publication Photosynthetic carbon uptake correlates with cell protein content during lipid accumulation in the microalgae Chlorella vulgaris NIES 227.

This repository contains two files:
  1) Jumbo_paper.rmd: R markdown document in which all analyses associated to the publication Photosynthetic carbon uptake correlates with cell protein content during lipid accumulation in the microalgae Chlorella vulgaris NIES 227 are carried out. In this script, data formatting, statistical analysis, model development and figure elaboration are notably performed.
  2) o2_cell_light_local_interpol.R: R script containing a function used in analyses carried out in the Jumbo_paper.rmd script. This function aims at computing a light field in the oximetric appartus from Qubit, based on incident light intensity and optical properties of the algae broth it contains.

In order to reproduce the results of the study, both script of this repository must be placed in the same working directory. The study results file Results_jumbo.xlsx (available at https://doi.org/10.6084/m9.figshare.c.6229317.v1) must also be placed in the same directory. Jumbo_paper.rmd can then be simply run hence producing all the results and figures of the publication Photosynthetic carbon uptake correlates with cell protein content during lipid accumulation in the microalgae Chlorella vulgaris NIES 227.
