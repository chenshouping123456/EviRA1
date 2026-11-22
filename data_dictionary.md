# EviRA: Confidence-Weighted Evidence-Graph Framework

This repository contains the code, data schemas, and evaluation benchmarks for the paper:
**"EviRA: A Confidence-Weighted Evidence-Graph Framework for Health-Informatics-Guided Literature Mining, with an Identifiability Boundary for Abstract-Level Evidence"** (Submitted to *Methods of Information in Medicine*).

## Overview
EviRA is a framework that encodes clinical literature as a confidence-weighted heterogeneous graph of documents, syndromes, formulas, and herbs. It aims to turn "frequency is not evidence" into an auditable and reproducible informatics operation.

## Repository Structure
- `data/`: Contains the 30-record gold standard, controlled vocabularies, and the 107-field data dictionary.
- `scripts/`: Python scripts for rule-based extraction, blind LLM extraction, and Evidence-Weight Propagation (EWP).
- `evaluation/`: Scripts for calculating micro-F1, Spearman rho, and permutation tests.
- `search_log/`: Exact CNKI search expressions and export counts.

## Reproducibility & Data Availability
- **Full Paper Dataset:** (Upon acceptance) The de-duplicated 2,365-record dataset will be archived at **[Zenodo DOI: to be inserted]**.
- **Environment:** The code is written in Python 3.10+. Dependencies are listed in `requirements.txt`.

## Contact
For any questions regarding the code or data, please contact: 295256318@qq.com
