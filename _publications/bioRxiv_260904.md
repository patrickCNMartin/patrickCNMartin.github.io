---
title: "Cross-domain confidence reliability and remappability of frozen single-cell representations"
collection: publications
category: preprints
excerpt: 'To address this, we introduce an audit framework to systematically evaluate the confidence estimates derived from the training set (source) against the realities of the target test set. We demonstrate that raw MSP fundamentally fails to represent true confidence when applied to target datasets.'
date: 2026-09-04
venue: 'bioRxiv'
paperurl: 'https://doi.org/10.64898/2026.08.31.748446'
citation: 'Guangzheng Weng, Danfei Zhu, Yufei Zhao, Patrick C Martin, Hyobin Kim, Junghyun Jung, Gi-Hoon Nam, Kyoung Jae Won. Cross-domain confidence reliability and remappability of frozen single-cell representations. bioRxiv 2026.08.31.748446 (2026). https://doi.org/10.64898/2026.08.31.748446'
---

Single-cell foundation models are increasingly adopted for downstream applications such as cell-type prediction. However, these predictions are often utilized without assessing their reliability, or by relying on a simple cutoff applied to the maximum softmax probability (MSP) derived from the classifier. This raises a critical question: can raw MSP be trusted as a reliable measure of confidence on unseen data (target) exhibiting diverse technical and biological variations? To address this, we introduce an audit framework to systematically evaluate the confidence estimates derived from the training set (source) against the realities of the target test set. We demonstrate that raw MSP fundamentally fails to represent true confidence when applied to target datasets. By decomposing the confidence gap between source and target data, we reveal that these discrepancies stem from a combination of rank-ordering errors and systemic probability drift. We further show that the drift can be successfully recalibrated by leveraging a small subset of labeled target data. While this recalibration improves the reliability of automated acceptance, it inherently introduces a trade-off by increasing the volume of cells requiring manual review. Ultimately, our framework establishes that the safe deployment of these models necessitates target-specific confidence adjustment using representative local labels.
