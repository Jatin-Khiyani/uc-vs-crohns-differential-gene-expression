# UC vs Crohns Differential Gene Expression

This repository is in its initial phase and is currently under development.

This repository presents a bioinformatics project focused on differential gene expression analysis between Ulcerative Colitis and Crohn’s Disease using the GEO dataset GSE235236

## Data Cleaning

1. Basic string processing was performed to clean and standardize column names.
1. Counts Per Million (CPM) normalization was applied to account for differences in sequencing depth across samples.
1. Genes were filtered based on CPM values, retaining only those with expression levels greater than 10.
