# LymphoSeq
This R package analyzes high-throughput sequencing of T and B cell receptor
complementarity determining region 3 (CDR3) sequences generated by [Adaptive
Biotechnologies' ImmunoSEQ assay](http://www.adaptivebiotech.com/immunoseq).

### Installation instructions

#### Install release version 1.4
###### Install from [Bioconductor](https://www.bioconductor.org/packages/LymphoSeq)
```
if (!requireNamespace("BiocManager", quietly=TRUE))
    install.packages("BiocManager")
BiocManager::install("LymphoSeq")
```

#### Install developer version 1.5
###### Option 1:  Install from [Bioconductor developer branch](https://www.bioconductor.org/developers/how-to/useDevel/)
```
# Switch to Bioconductor developer branch (requires latest version of R)
library(BiocManager)
BiocManager::install(version = "devel")

# Download developer release
if (!requireNamespace("BiocManager", quietly=TRUE))
    install.packages("BiocManager")
BiocManager::install("LymphoSeq")
```
###### Option 2:  Install from GitHub
```
# Install the latest version of Bioconductor
if (!requireNamespace("BiocManager", quietly=TRUE))
    install.packages("BiocManager")
BiocManager::install()

# Download developer tools
install.packages("devtools")

# Download package from GitHub
devtools::install_github("davidcoffey/LymphoSeqDB")
devtools::install_github("davidcoffey/LymphoSeq")
```

### Documentation
* [LymphoSeq vignette](http://bioconductor.org/packages/release/bioc/vignettes/LymphoSeq/inst/doc/LymphoSeq.html)
* [LymphoSeq manual](https://bioconductor.org/packages/release/bioc/manuals/LymphoSeq/man/LymphoSeq.pdf)
* [LymphoSeq news](https://bioconductor.org/packages/release/bioc/news/LymphoSeq/NEWS)

### Citation
Coffey D (2017). LymphoSeq: Analyze high-throughput sequencing of T and B cell receptors. R package version 1.4.
