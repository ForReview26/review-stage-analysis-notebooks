# Review-Stage Analysis Notebooks

This repository contains anonymized, output-cleared Jupyter notebooks for peer review.

The notebooks reproduce review-stage analyses from data materials shared separately through OSF. They do not include raw data files, derived output tables, model checkpoints, figures, or API-based annotation code.

## Contents

- `notebooks/01_existing_data_analyses.ipynb`
  - Paired hard-vs-soft comparisons
  - Aspect-level class-wise metrics
  - Entropy routing summaries
  - Multi-LLM robustness summaries
- `notebooks/02_human_validation_and_tableS2.ipynb`
  - Human-validation audit summaries
  - Human/AI/released-label agreement tables
  - Supplementary original-vs-AI confusion table logic

## Data

Download the OSF review data package and place it under `data/` using the layout expected in the notebook configuration cells. Alternatively, set `DATA_ROOT` to the downloaded data directory before running.

Generated files are written to `outputs/` by default and are intentionally excluded from version control.

## Review-Stage Notes

The repository is prepared for anonymous peer review. Author-identifying metadata, local machine paths, API keys, and notebook cell outputs have been removed from the shared notebook copies.
