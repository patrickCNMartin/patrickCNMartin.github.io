---
title: "LabBrain"
excerpt: "LabBrain: tools and skills for AI agents that read and maintain a lab wiki."
collection: software
date: 2026-10-01
---

LabBrain provides the tools and skills for AI agents that read and maintain a lab wiki written in the [Open Knowledge Format](https://github.com/GoogleCloudPlatform/knowledge-catalog/blob/main/okf/SPEC.md) (OKF).

The work is split between code and models:

* Code does everything that can be worked out from file names, paths, dates and git hashes: headers, provenance, index listings, and staleness and drift bookkeeping
* An LLM is only called where a note has to be read: writing summaries, and checking that they still say what their notes say

Any LLM can be used, either by hand or in unattended overnight runs. Each lab's wiki evolves its own skills, and skills that work beyond one lab are contributed back to the shared repository.

## Role

Core developer and project lead, leading a team of developers and validators.

## GitHub Page

[LabBrain](https://github.com/lehtiolab/LabBrain)
