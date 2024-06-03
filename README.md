# T2T_KaryoploteR
my genome file is based on https://www.ncbi.nlm.nih.gov/datasets/genome/GCF_009914755.1/.

my cytobands file is based on https://github.com/marbl/CHM13?tab=readme-ov-file.


# Usage
```R
library(karyoploteR)
custom.genome <- toGRanges("~/Downloads/mygenome_T2T.tsv")
custom.cytobands <- toGRanges("~/Downloads/chm13v2.0_cytobands_allchrs.txt")
kp <- plotKaryotype(genome = custom.genome, chromosomes = "all", cytobands = custom.cytobands)
```
