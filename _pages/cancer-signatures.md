---
defaults:
  # _pages
  - scope:
      path: ""
      type: pages
author_profile: true
layout: single
title: "Mutational signatures and their impact on protein structures"
permalink: /cancer-signatures/
---

In this project we ask whether different mutational signatures (combinations of mutable DNA motifs) can pose different impact on the affected proteins. Different proteins have different structural folds; these features and the local physicochemical environment dictates the distribution of amino acids along the protein sequence and hence should provide different availability of DNA motifs for mutational process to act upon. In this project I undertook a computational analyses of observed somatic mutations as well as mutational scanning of human coding sequences to ask whether some mutable DNA motifs can be potentially more harmful than others, and its delicate balance with conservation of protein sequence, structure and function.

I began working in this area during my PhD and contributed towards [ZoomVar](http://fraternalilab.kcl.ac.uk/ZoomVar), an analysis of mapping protein missense variants from health and disease to protein structure, protein stability and abundance data.

**Publications**

**Ng JCF**, Fraternali F. Protein structural consequences of DNA mutational signatures: A meta-analysis of somatic variants and deep mutational scanning data. *bioRxiv* 2021 doi: <https://doi.org/10.1101/2021.05.27.445950>

Laddach A, **Ng JCF**, Fraternali F. Pathogenic missense protein variants affect different functional pathways and proteomic features than healthy population variants. *PLoS Biol.* 2021 (Accepted)

**Materials**

*Repository*

On [BitBucket](https://bitbucket.org/josef0731/zoomvarsomaticmutsig/src/master/).

*R markdown*

HTML knitted version of R markdown documents containing all code & analysis undertaken in this project. The raw R markdown files can be found in the links provided below.

Annotating TCGA variants in terms of protein (structural) consequences | [HTML notebook](https://htmlpreview.github.io/?https://bitbucket.org/josef0731/zoomvarsomaticmutsig/raw/68e530dde539131eb21a14bd702591fb8156236d/Analysis/variants_structure.html) | [R markdown code](https://bitbucket.org/josef0731/zoomvarsomaticmutsig/src/master/Analysis/variants_structure.Rmd)
Selection pressure in protein surface and core | [HTML notebook](https://htmlpreview.github.io/?https://bitbucket.org/josef0731/zoomvarsomaticmutsig/raw/3ca18f9d60630ca00db480717be25fe3be0446c0/Analysis/variants_selection.html) | [R markdown code](https://bitbucket.org/josef0731/zoomvarsomaticmutsig/src/master/Analysis/variants_selection.Rmd)
Annotating mutational signatures in terms of protein (structural) consequences | [HTML notebook](https://htmlpreview.github.io/?https://bitbucket.org/josef0731/zoomvarsomaticmutsig/raw/3b90c5df5953470016396cb2dac7bf37b785cbe1/Analysis/variants_signature.html) | [R markdown code](https://bitbucket.org/josef0731/zoomvarsomaticmutsig/src/master/Analysis/variants_signature.Rmd)
Protein impact of SNVs occuring in different mutational contexts | [HTML notebook](https://htmlpreview.github.io/?https://bitbucket.org/josef0731/zoomvarsomaticmutsig/raw/3b90c5df5953470016396cb2dac7bf37b785cbe1/Analysis/SatMutSignatures.html) | [R markdown code](https://bitbucket.org/josef0731/zoomvarsomaticmutsig/src/master/Analysis/SatMutSignatures.Rmd)
Compare homologues in terms of availability of mutatable motives | [HTML notebook](https://htmlpreview.github.io/?https://bitbucket.org/josef0731/zoomvarsomaticmutsig/raw/3b90c5df5953470016396cb2dac7bf37b785cbe1/Analysis/compareHomologues.html) | [R markdown code](https://bitbucket.org/josef0731/zoomvarsomaticmutsig/src/master/Analysis/compareHomologues.Rmd)

*Web-app*

[ZoomvarTCGA](http://fraternalilab.kcl.ac.uk/ZoomVar/ZoomvarSomatic) is a R shiny web application which allows user to browse pre-computed mapping of TCGA, ICGC Metastatic tumour and HipSci iPSCs variants to protein structure. It provides data presentation and visualisation tools to browse data generated in this project, and interactively visualise missense variations mapped to structures from the Protein Data Bank (PDB).
