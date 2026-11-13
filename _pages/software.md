---
layout: archive
title: "Software"
permalink: /software/
author_profile: true
---

<!-- 
{% include base_path %}

{% for post in site.writing reversed %}
  {% include archive-single.html %}
{% endfor %}
-->

A non-exhaustive list of coding and analysis projects

# Software Packages

## [metaSolid](https://github.com/patrickCNMartin/metaSolid)
Python package which integrates local/cloud LLMs and semantic embeddings models to generate harmonized meta data fields. Harmonization can results from semantic clustering or against a common target.

## [Hermetica](https://github.com/patrickCNMartin/Hermetica)
Protocol version control. Pulls wet lab protocols from multiple sources and provides strict version control by generating a protocol lock file. Wet lab pipeline using multiple protocols are converted into DAG that are also tracked and version controlled. 

## [Iris](https://github.com/patrickCNMartin/Iris)
OCR + LLM lab note augmentation. Scanned lab notes are converted to markdown by OCR, then a local LLM corrects OCR errors and translates non-English text. Context documents, such as Hermetica protocol lock files, are used to fill gaps and fix values. Everything runs locally.

## [Timekeeper](https://github.com/patrickCNMartin/timekeeper)
Mac and Windows app for core facility meetings. Pulls recent service requests from the iLab API and builds the meeting PowerPoint deck and a TSV summary table comparing requested and submitted samples.


---


## [Vesalius](https://github.com/WonLab-CS/Vesalius)
Dissecting Tissue Anatomy From Spatial Transcriptomics data and Mapping heterogenous Spatial data.


---

## [Bombadillo](https://github.com/patrickCNMartin/bombadillo)
Spatial Omics simulator including cell-cell interactions.



---

## [Kuresi](https://github.com/patrickCNMartin/Kuresi)
Assessing Cancer Competivity through ELO style DEG tournaments.


---

## [ChIPanalyser](https://www.bioconductor.org/packages/release/bioc/html/ChIPanalyser.html)
Bioconductor package to predict Transcription Factor Binding to DNA using a statistical thermodynamic framework and evolutionary optimization.


---


# Analysis

## [Vesalius Analysis](https://github.com/WonLab-CS/Vesalius_analysis)
Analysis repository for Vesalius 2.0.0. (Nature Communications).

---


## [SPIX Analysis](https://github.com/patrickCNMartin/scSPIX_analysis)
Nextflow pipeline with containers (Docker and Apptainer) with all the analysis related to the Super Pixel (SPIX) project.

Development enviroment handled with Nix.

---

## [GAND](https://github.com/patrickCNMartin/GAND)
Nextflow pipeline with conda environments with all the analysis related to the GAND Neuro-degenerative diseases project.

Conda will replaced with containers at publication time. 

---