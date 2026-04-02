# BIS – Emergency Department Process Mining (Exam Call 18.12.2025)

This repository contains a complete Process Mining analysis of an Emergency Department (ED) patient treatment process, aligned with the exam assignment:

- preprocessing (cleaning + filtering),
- performance analysis,
- process discovery,
- conformance checking,
- improvement identification,
- additional question: pattern‑based feature generation for semantic variant analysis.

Note: the original exam dataset is confidential. This repository uses a synthetic experimental dataset (`UpFLux_Healthcare_Database_labeled.csv`) that mimics the structure and typical behavior of an ED event log.

## Repository structure
.
├── BIS_Exam_02042026.ipynb   # Main notebook (fully commented)
├── UpFLux_Healthcare_Database_labeled.csv   # Experimental synthetic dataset (generated/downloaded from the notebook)
├── environment.yaml                         # Conda environment for reproducibility
└── README.md                               # This file

## Reproducible environment (Conda)
Create and activate the environment
```bash
conda env create -f environment.yaml
## Contributing
Feel free to extend the notebook with additional process‑mining techniques, visualisations, or data‑quality checks. Commit and push your changes to keep the repository up‑to‑date.
