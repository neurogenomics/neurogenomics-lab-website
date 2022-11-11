---
title: New R tool for the comprehensive standardisation and quality control of
  GWAS summary statistics
date: 2021-10-06T14:07:51.431Z
draft: false
featured: false
image:
  filename: featured
  focal_point: Smart
  preview_only: false
authors: Nathan Skene
---
We are delighted to announce the publication of MungeSumstats, a Bioconductor R package for the standardisation and quality control of many GWAS summary statistics in [Bioinformatics](https://academic.oup.com/bioinformatics/advance-article/doi/10.1093/bioinformatics/btab665/6380562).

The package was developed in the group by Alan Murphy, Brian Schilder and Nathan Skene to address the disparity across how the results of GWAS are stored and shared. The aim was to enable painless and rapid meta-analysis for researchers by ensuring whatever GWAS results they use can be standardised, avoiding spurious results.

The package can handle a variety of input file types and implements more than 35 checks on the inputted summary statistics including the use of reference genomes to ensure consistent allelic direction and correct annotation of SNPs. The package can also convert the reference genome of the dataset, offers a choice of output file types; tsv, LDSC ready, VCF & R native objects, and is integrated with IEU GWAS VCF to directly import and standardise their VCFs. More information on the package is available on its [website](https://neurogenomics.github.io/MungeSumstats/articles/MungeSumstats.html).
