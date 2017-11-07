# Subnetwork Identification Visualization
This is a source code of our publication.

## Description

## File Description
1. Data Preprocessing
2. Significant Gene Identification
3. Dissimilarity Measure
This step, we made use Weighted Gene-Co Expression Network Analysis or "WGCNA" Library in R.
4. Pattern Analysis


## Installation
1. Required library
For the first time, you might need to install "WGCNA", "knitr" and "igraph"

```
# Necessary packages for GCN construction
source("http://bioconductor.org/biocLite.R") 
biocLite(c("AnnotationDbi", "impute", "GO.db", "preprocessCore")) 
install.packages("WGCNA")
install.packages("knitr", dependencies = TRUE)
install.packages("igraph")
```
