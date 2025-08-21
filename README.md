# Dopamine_Xspecies

This R project performs a preliminary analysis of single-nucleus RNA-seq data from non-human primate striatum.
It focuses on differential gene expression and epigenetic regulation between DRD1 and DRD2 medium spiny neurons (MSNs).

## Data Source
GSE167920 - https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE167920
"GSE167920_Results_full_nuclei_processed_final.rds.gz"

## Main Analysis
- Subset DRD1 vs DRD2 MSNs
- Differential gene expression analysis
- Pathway enrichment using `clusterProfiler`
- Epigenetic regulator analysis

## How to Run
Open `Dopamine_MSN_Epigenetics.Rproj` in RStudio and knit `scnuclei_reanalysis.Rmd`.
