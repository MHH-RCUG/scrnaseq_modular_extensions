# scrnaseq_modular_extensions
UNDER DEVELOPMENT: Workflows for modular extensions of single-cell RNA-seq analysis performed with the scrnaseq script https://github.com/ktrns/scrnaseq 

This repository contains small R markdown scripts with diverse workflows for modular extensions of single-cell RNA-seq analysis performed with the scrnaseq script https://github.com/ktrns/scrnaseq. That means, all scripts use the output of the scrnaseq script and perform additional analysis such as cluster annotation with reference using SingleR and Clustifyr or pseudotime analysis via Monocle 3 upon it with the results being returned as html report.  

The libraries that need to be loaded are called in the beginning of each script.
For more specific details regarding the software and packege versions that were tested, please see the section "Parameters and software versions" at the end of the example html reports.

The dataset that was used to generate the example html reports originates from the 10x dataset "1k Peripheral blood mononuclear cells (PBMCs)" (https://support.10xgenomics.com/single-cell-gene-expression/datasets/3.0.0/pbmc_1k_v3). This dataset was used to create two artifical samples (sample1 and sample2) with 250 cells and 6000 genes each in a project called pbmc_small and process is utilizing the crnaseq script https://github.com/ktrns/scrnaseq.

