## 🐚 Limpet Grazing on Microalgae – R Analysis

These data are from LaScala-Gruenewald et al. 2016, Marine Ecology Progress Series http://doi.org/10.3354/meps11774

This repository contains R code and data used to analyze the effects of limpet grazing on microalgal communities in the upper intertidal zone
# Summary
The study explore how limpet grazing effect the microalgae community

# Required Files
microalgae_community_SEM_data.csv: Dataset with percent cover of microalgae morphotypes from SEM imaging.
LaScala-Gruenewald_etal_MEPS_2016.pdf: Source paper describing the experimental setup and findings.

# Methods
- Statistical Analysis: NMDS, PERMANOVA, CLR tranformation, PCA on clr, Alpha diversity
- Transformations: CLR transformation
- Diversity Metrics: Richness and composition of microalgae morphotypes analyzed.
- Visualization: Barplots, and ordination plots created with vegan and ggplot2.

# Reference
LaScala-Gruenewald, D. E., Miller, L. P., Bracken, M. E. S., Allen, B. J., & Denny, M. W. (2016). Quantifying the top-down effects of grazers on a rocky shore: selective grazing and the potential for competition. Marine Ecology Progress Series, 553, 49–66. https://doi.org/10.3354/meps11774

# Instruction :
Open the R project or LimpetGrazing.Rmd file in RStudio.
Knit the R Markdown document to generate a full report of the analysis.
