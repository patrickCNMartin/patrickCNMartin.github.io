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

## [LabBrain](https://github.com/lehtiolab/LabBrain)
Core developer and project lead, leading a team of developers and validators. Tools and skills for AI agents that read and maintain a lab wiki in the Open Knowledge Format (OKF). Code handles provenance, git-hash tracking, index listings and staleness checks; an LLM is only called where a note has to be read, to write summaries and check them for drift.

## [metaSolid](https://github.com/patrickCNMartin/metaSolid)
Python package which integrates local/cloud LLMs and semantic embeddings models to generate harmonized meta data fields. Harmonization can result from semantic clustering or against a common target.

## [Hermetica](https://github.com/patrickCNMartin/Hermetica)
Protocol version control. Pulls wet lab protocols from multiple sources and provides strict version control by generating a protocol lock file. Wet lab pipeline using multiple protocols are converted into DAG that are also tracked and version controlled. 

## [Iris](https://github.com/patrickCNMartin/Iris)
OCR + LLM lab note augmentation. Scanned lab notes are converted to markdown by OCR, then a local LLM corrects OCR errors and translates non-English text. Context documents, such as Hermetica protocol lock files, are used to fill gaps and fix values. Everything runs locally.

## [Timekeeper](https://github.com/patrickCNMartin/timekeeper)
Mac and Windows app for core facility meetings. Pulls recent service requests from the iLab API and builds the meeting PowerPoint deck and a TSV summary table comparing requested and submitted samples.


---


## [Vesalius](https://github.com/WonLab-CS/Vesalius)
Dissecting Tissue Anatomy From Spatial Transcriptomics data and Mapping heterogeneous Spatial data.


---

## [Bombadillo](https://github.com/patrickCNMartin/bombadillo)
Spatial Omics simulator including cell-cell interactions.



---

## [Kuresi](https://github.com/patrickCNMartin/Kuresi)
Assessing Cancer Competitiveness through ELO style DEG tournaments.


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

Development environment handled with Nix.

---

## [GAND](https://github.com/patrickCNMartin/GAND)
Nextflow pipeline with conda environments with all the analysis related to the GAND Neuro-degenerative diseases project.

Conda will be replaced with containers at publication time. 

---