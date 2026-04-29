[![DOI](https://zenodo.org/badge/1220020630.svg)](https://doi.org/10.5281/zenodo.19855487)

# SGD_gutmicro_2026
Data and code for the paper: "Gut Microbiota in Preterm infants with different weight gain outcomes"

# Procedure

You must run the R markdowns (Scripts/Rmds) in the following order so that the appropriate RData files are generated:
1) Shotgun_preamble.Rmd
2) Shotgun_taxonomic_growth_analysis.Rmd
3) Download the [KEGG data files from Zenodo](https://doi.org/10.5281/zenodo.19854903) and place in Data/
4) Shotgun_gene_abundance_analysis.Rmd
5) Shotgun_metabolomic_analysis.Rmd
6) Shotgun_random_forest_analysis.Rmd
7) FIGURESANDTABLES.Rmd
8) The Rmds in sensitivity/

# Source data

Decontaminated Fastq's are available from the following BioProjects:
- https://www.ncbi.nlm.nih.gov/bioproject/PRJNA1301887
- https://www.ncbi.nlm.nih.gov/bioproject/PRJNA872399

Metabolomic data is under Data/

# Manuscript

[TBD]
