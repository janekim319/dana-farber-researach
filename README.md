# Dana Farber Research Summer 2021

Summer of 2021, I worked at Dr. Shirley Liu's Lab at the Dana Farber Cancer Institute with the guidance of Tommy (Ming) Tang, a senior scientist in the lab. I focused on single cell ATAC-seq data and their analysis. Specifically, I investigated how the different count matrices affect the clustering results (bin count matrix vs peak count matrix). This investigation is important in collecting public scATAC-seq data and building a database that supports data integration across different studies. 

The two main tools I used are MAESTRO and ArchR. On a High Computing Server, I performed analysis on the scATAC-seq multiome data obtained from 10X genomics using MAESTRO, developed by the Liu Lab. I also ran ArchR using RStudio on the same data to compare the clustering results of the two tools. I also used the Seurat package to transfer the cell annotations from scRNA-seq data to scATAC-seq data in multiome data. 

Every week, I presented my results to the lab, consisted of scientists working on single cell data analysis. The slides from the 3 presentations can be found below.

## Documentations for ArchR

ArchR Github Page: https://github.com/GreenleafLab/ArchR/discussions

ArchR Full Tutorial: https://www.archrproject.com/bookdown/getting-started-with-archr.html

ArchR Function Descriptions: https://www.archrproject.com/reference/index.html

ArchR Multiome PBMC 10X data analysis: https://greenleaflab.github.io/ArchR_2020/Ex-Analyze-Multiome.html

## Link to Download the scATAC-seq data
https://support.10xgenomics.com/single-cell-multiome-atac-gex/datasets/1.0.0/pbmc_granulocyte_sorted_10k

## Tutorial for MAESTRO
https://baigal628.github.io/MAESTRO_documentation/multi-scatac.html

## Other useful packages and installations
For Pairwise Comparison of the Clusters: https://crazyhottommy.github.io/EvaluateSingleCellClustering/mixture_tidy_idents.html

## Annotating scATAC-seq cells using scRNA-seq data
https://satijalab.org/seurat/articles/atacseq_integration_vignette.html

## Presentation Slides

Comparing two different count matrices: bin method vs peak calling
[Count Matrix Generation_ Bin Method vs Peak Calling.pdf](https://github.com/janekim319/dana-farber-research/files/6978313/Count.Matrix.Generation_.Bin.Method.vs.Peak.Calling.pdf)

Part 1 of Comparing the clustering results of ArchR and MAESTRO
[ArchR vs MAESTRO Clustering Comparison.pdf](https://github.com/janekim319/dana-farber-research/files/6978318/ArchR.vs.MAESTRO.Clustering.Comparison.pdf)


Part 2 of Comparing the clustering results of ArchR and MAESTRO
[ArchR vs MAESTRO comparison Part 2.pdf](https://github.com/janekim319/dana-farber-research/files/6978317/ArchR.vs.MAESTRO.comparison.Part.2.pdf)




