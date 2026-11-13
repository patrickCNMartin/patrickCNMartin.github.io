---
title: "Iris"
excerpt: "Iris: OCR and LLM augmentation of scanned lab notes."
collection: software
date: 2026-11-01
---

Iris turns scanned lab notes (PDF, PNG, JPG) into corrected, searchable markdown. Scans are read by an OCR model (Chandra OCR 2), then a local LLM served by Ollama corrects what the OCR misread and translates any non-English text into English. Everything runs locally, so lab notes never leave the machine.

When a context document for the same work exists, such as a markdown protocol or a Hermetica protocol lock file, the LLM uses it to fill gaps and fix values in the note.

* The raw OCR is kept next to the corrected note, as a record of what the scan said before the LLM touched it
* Long OCR runs resume page by page after an interruption
* Scans are paired with their context documents by file name

## GitHub Page

[Iris](https://github.com/patrickCNMartin/Iris)

## Related Software

[Hermetica](https://github.com/patrickCNMartin/Hermetica)

## Publications
In progress
