---
title: "A Generalizable Transformer Framework for Gene Regulatory Network Inference from Single-Cell Transcriptomes"
collection: publications
category: manuscripts
permalink:  https://doi.org/10.1002/aisy.202500781
excerpt: 'Here, we present FTGRN (Foundation Transformer for Gene Regulatory Networks), a universal framework for GRN inference based on a pretrain–finetune paradigm. FTGRN integrates gene embeddings derived from Generative Pre-trained Transformer-4 (GPT-4) with publicly available chromatin immunoprecipitation sequencing (ChIP-seq) data to construct a regulatory knowledge base for pretraining a Transformer-based graph neural network.'
date: 2026-01-15
venue: 'Advanced Intelligent Systems'
paperurl: 'https://doi.org/10.1002/aisy.202500781'
citation: 'GuangzhengWeng, HyobinKim, PatrickMartin, JunilKim, Tae-HyungKim, Gi-HoonNam, DonghaKim, Kyoung JaeWon. Adv. Intell. Syst.. 2025; 000, e202500781. https://doi.org/10.1002/aisy.202500781'
---

Gene regulatory network (GRN) inference has advanced substantially through supervised and unsupervised learning approaches; however, many existing methods require extensive computational resources and exhibit limited generalizability across biological contexts. In addition, they do not fully exploit the growing availability of large-scale transcriptomic and regulatory data. Here, we present FTGRN (Foundation Transformer for Gene Regulatory Networks), a universal framework for GRN inference based on a pretrain–finetune paradigm. FTGRN integrates gene embeddings derived from Generative Pre-trained Transformer-4 (GPT-4) with publicly available chromatin immunoprecipitation sequencing (ChIP-seq) data to construct a regulatory knowledge base for pretraining a Transformer-based graph neural network. The pretrained model is subsequently fine-tuned using single-cell RNA sequencing (scRNA-seq) data to infer context-specific regulatory networks. Leveraging its pretrained foundation, FTGRN enables near real-time GRN inference, generating networks for 2,000 genes in under 30 seconds, substantially outperforming state-of-the-art methods in both speed and predictive accuracy. Application to amino acid–starved mouse embryonic fibroblasts demonstrated that FTGRN accurately reconstructs stress-response GRNs and identifies key regulators, including C/EBPγ, c-Jun, DDIT4, and c-Fos. Collectively, FTGRN provides a scalable, adaptable, and interpretable framework for GRN inference in single-cell genomics.

