---
defaults:
  # _pages
  - scope:
      path: ""
      type: pages
author_profile: true
layout: single
title: "Sequence variations of immune receptors"
permalink: /immune-sequences/
---

This has been a research direction I pursue since my post-doc days. I conduct large-scale computational analysis of the *in vivo* antibody repertoire and data from *in vitro* studies of B cell biology.

This has resulted in a number of bioinformatics tools to analyse antibody sequence variations using data generated with high-throughput sequencing methods. We analyse variations in terms of CSR, somatic hypermutation (SHM) and other diversification mechanisms observed in variable regions of antibodies.

**Code**

[sciCSR](https://github.com/Fraternalilab/sciCSR): R package for detecting sterile and productive immunoglobulin transcripts from scRNA-seq sequencing data of B cells, and use these signals to build models to describe transitions between B cell states.

[ImmunoMatch](https://github.com/Fraternalilab/ImmunoMatch): A fine-tuned antibody language model for the identification of cognate paired immunoglobulin Heavy (H) and Light (L) chains. Trained from single-cell paired H-L amino acid sequences, we showed that the ImmunoMatch model reveals insights into how chain pairing propensity changes across B cell maturation stages and explored how this can be game-changing in antibody discovery pipelines from spatial transcriptomics datasets.

[BrepConvert](https://github.com/Fraternalilab/BrepConvert): R package for flexible and detailed annotation of gene conversion events in immunoglobulin repertoire. Designed to analyse repertoire data from primates such as chicken, rabbit etc where gene conversion is prevalent to generate antibody diversity.

[BrepPhylo](https://github.com/Fraternalilab/BrepPhylo): R package for fast lineage reconstruction, enabling analysis on large samples of clonotypes from BCR repertoire data.

[scRNAVeloQuant](https://github.com/Fraternalilab/scRNAVeloQuant): R code snippet to quantify transitions between cell types from RNA velocity estimates in single-cell RNA sequencing data analysis.

**Publications**

Please refer to below for some of my key papers in this area:

Ng JCF, Montamat Garcia G, Stewart AT et al. sciCSR infers B cell state transition and predicts class-switch recombination dynamics using single-cell transcriptomic data. *Nat Methods* 21, 823–834 (2024). <https://doi.org/10.1038/s41592-023-02060-1>

Guo D, Dunn-Walters DK, Fraternali F & Ng JCF. ImmunoMatch learns and predicts cognate pairing of heavy and light immunoglobulin chains. *Nat Methods* (2025). <https://doi.org/10.1038/s41592-025-02913-x>