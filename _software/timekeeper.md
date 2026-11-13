---
title: "Timekeeper"
excerpt: "Timekeeper: core facility meeting reports from iLab."
collection: software
date: 2026-09-01
---

Timekeeper is a small Mac and Windows desktop app for core facility meetings. It pulls a core's recent service requests from the iLab API and builds the meeting material automatically:

* A PowerPoint deck with one slide per new start-up meeting and supplementary sample submission, and summary tables for assigned, in-processing and ready-to-bill projects
* A TSV table with one row per request, comparing the number of samples requested with the number actually submitted, alongside sample type, organism, clinical status and key dates
* Optionally, a JSON export of everything iLab holds on those requests

The API token is stored in the system keychain (macOS Keychain or Windows Credential Manager), never in a file.

## GitHub Page

[timekeeper](https://github.com/patrickCNMartin/timekeeper)
