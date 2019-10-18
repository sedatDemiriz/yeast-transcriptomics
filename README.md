# Transcriptomics in yeast
Yeasts (Saccharomyces cerevisiae) are used in the production of some of our diet's most cherished choices such as bread (not to mention wine and beer). There are many other biotechnology applications that use yeast, some of which include complex pharmaceuticals production. Yeasts are also great model organisms because of their simple and small genome consisting of approximately 6000 genes. Being unicellular organisms also make them great for transcriptome analyses as gene expression is homogenous. As part of our Vancouver-based hackathon (hackseq19) project (October 18 to 20, 2019) we will be examining a yeast transcriptome dataset. The data was gathered from a number of yeast strains that have been treated with various stimuli, and gene expression changes the readout. Expression is normalized to Transcript Per Million (TPM). As a team, we will be cleaning, analyzing, and communicating the results of our explorations through clear documentation of procedures and an interactive application.

### Data
The data in this project includes gene expression values for 92 yeast strains treated with various stimuli. RNA expression levels are normalized to TPM (transcripts per million), following a default normalization procedure. Data is stored in `data` folder.
- The `SC_expression.csv` file contains gene expression of yeast strains in the experiments.
- The `labels.csv` files pertain to gene validation status and molecular function (MF), cellular component (CC), and biological processes (BP) of those genes. 
- The `conditions_annotation.csv` file explain the yeast strains and experimental conditions.

### Data Source 
This project is inspired by the yeast-omics dataset shared as a kaggle competition, and the original data can be found [here](https://www.kaggle.com/costalaether/yeast-transcriptomics).

### Goal
The goal of this project is to unravel the genetic mechanisms involved in yeast stress adaptation by building a visualization platform (e.g. shiny application) that allows scientists to explore the data interactively.

The tasks we will attempt in the hackathon include:
- Perform unsupervised and supervised clustering of expression data
- Perform gene set enrichment analyses (GSEA, ReactomePA)
- Create visualizations of results (heatmaps, barplots, etc.)
- Phylogenetic/Taxonomic trees for yeast strains

### Skills - (Remove?)
You will need introductory knowledge of R, RNA expression analysis workflows, design thinking, and coding skills. Coding in R (or Python) and basic knowledge of git/github is an asset. Team communications will happen in person and in [slack](hackseq19.slack.com).

### Software - (Change up for users, rather than our group?)
Please have the latest versions of R and R Bioconductor installed on your machine prior to the workshop. RStudio (the free version) is highly recommended as well, since we will be teaching in this environment.

- [Install R](https://cran.r-project.org/)   
- [Install R Bioconductor](https://bioconductor.org/install/)   
- [Install RStudio](https://rstudio.com/products/rstudio/download/#download)   

### Suggested preparatory lessons - (Remove?)
- [Introduction to Data Science with R](http://shop.oreilly.com/product/0636920034834.do)
- [RNAseq Analysis tutorials in R](https://bioinformatics-core-shared-training.github.io/RNAseq-R/) and [Differential expression Analysis](https://combine-australia.github.io/RNAseq-R/06-rnaseq-day1.html)
- [Mastering Shiny](https://mastering-shiny.org/)
- [Data Manipulation and Visualization using R](http://bioinformatics-core-shared-training.github.io/r-intermediate/)
- [RNAseq data analysis workflow](https://github.com/griffithlab/rnaseq_tutorial) 
- [Setting up reproducible projects in R](https://nicercode.github.io/blog/2013-04-05-projects/) and [package management for reproducible R code](https://rviews.rstudio.com/2018/01/18/package-management-for-reproducible-r-code/) and [reproducibility good practices](https://github.com/karthik/rstudio2019)
- [Yeast pathway analysis in R](https://bioconductor.org/packages/release/bioc/vignettes/ReactomePA/inst/doc/ReactomePA.html)   
- [Additional resources from UCSF Data Science Initiative](https://courses.ucsf.edu/course/index.php?categoryid=499)
- [Package development, maintenance, documentation, and peer-review](https://devguide.ropensci.org/building.html#documentation)
- [Shiny Apps for Transcriptome Visualizations](https://academic.oup.com/bioinformatics/article/33/3/447/2525724)
- [RNAseq Shiny app options](https://www.rna-seqblog.com/tag/shiny/)


### Team Members
Noushin Nabavi, Matthew Emery, Alex Morin, Zuhaib Ahmed, Casey Engstrom, Sedat Demiriz, Shinta Thio, Saelin Bjornson
