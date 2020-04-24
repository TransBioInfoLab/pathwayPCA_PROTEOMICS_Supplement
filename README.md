# pathwayPCA Supplemental Materials for PROTEOMICS
### Supplemental documents for the PROTEOMICS manuscript of the `pathwayPCA` package


## Citing This Package
The paper is currently being revised for a resubmission to [PROTEOMICS](https://onlinelibrary.wiley.com/journal/16159861). Until this paper is accepted, you can cite our [bioRXiv pre-print](https://doi.org/10.1101/615435). We thank you, in advance, for any feedback you have!


## Reports
The main workflow document is written as a single report. We provide the rendered report in both MS Word (.docx) and Webpage (.html) forms. The packages you will need to replicate this work are:

- [`pathwayPCA`](https://doi.org/10.18129/B9.bioc.pathwayPCA) (Bioconductor)
- [`tidyverse`](https://www.tidyverse.org/) (CRAN)
- [`knitr`](https://yihui.org/knitr/) (CRAN)
- [`impute`](https://doi.org/10.18129/B9.bioc.impute) (Bioconductor)
- [`glmnet`](https://web.stanford.edu/~hastie/glmnet/glmnet_alpha.html) (CRAN)
- [`timeROC`](https://doi.org/10.1002/sim.5958) (CRAN)

Some of the computing takes a bit of time. On a 2016 MacBook Pro, the entire report will render in about an hour. Because of this, we give the RMarkdown document and the "knit" reports. You can choose to run only part of the examples and still check your ouptut against ours. If you find bugs in our code, please submit an issue at <https://github.com/gabrielodom/pathwayPCA/issues>.


## Data
**Assays:** The raw data files for these examples are too large to store on GitHub. Please check the `README.txt` file in `extdata/` for names, descriptions, and hyperlinks to the data files. Download these data files (**with no changes**) to your local copy of this `extdata/` directory (the report uses relative file paths for data import). The workflow manuscript contains all code necessary for data pre-processing and sample matching. If you pre-process the data in your own way, we can not claim that you will get similar results to what we have shown. 

**Pathway Collections:** We provide the pathway collections we used for analysis. You can use your own, but the results will likely be different (this is *pathway* PCA after all).

