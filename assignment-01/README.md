# Assignment 01 — Data Analysis with Python

Coursework for **CISC7204 – Data Science and Data Visualization** (University of Macau). This assignment covers the full data-analysis pipeline: importing data, wrangling, exploratory analysis, model development, and model evaluation. Notebooks are based on the IBM *Data Analysis with Python* labs.

> Only the core deliverables are kept here: `.ipynb` notebooks, the `.csv` datasets they load, and the project proposal `.docx`. Large screenshot folders, `.DS_Store`, `._*` metadata and `.ipynb_checkpoints` were removed. Original filenames are preserved.

## Modules

| Folder | Topic | What it covers |
| --- | --- | --- |
| `Module 1/` | Importing Datasets | Reading CSVs, assigning headers, replacing missing values, inspecting `dtypes`, `describe()` and `info()`; hands-on lab on a laptop-pricing dataset. |
| `Module 2/` | Data Wrangling | Handling missing data, correcting data formats, standardisation, normalisation, binning, and indicator (dummy) variables; exporting a cleaned CSV. |
| `Module 3/` | Exploratory Data Analysis | Descriptive statistics, continuous vs. categorical features, `groupby` / pivot tables, Pearson correlation and p-values. |
| `Module 4/` | Model Development | Simple and multiple linear regression, polynomial regression with pipelines, in-sample evaluation, and train/test splitting. |
| `Module 5/` | Model Evaluation and Refinement | Cross-validation, overfitting vs. polynomial order, ridge regression and alpha tuning, and grid search. |
| `Module 6/` | Final & Practice Projects | End-to-end **House Sales in King County** final project and an **Insurance Cost Analysis** practice project. |

## Files

- The `PreliminaryProjectProposal.docx` file in this folder — the preliminary project proposal for Assignment 01.
- Each `Module N/` folder contains two notebooks (a guided lab and a hands-on practice lab, or a final/practice project in Module 6) plus the CSV datasets used by that module. Duplicate dataset names (e.g. `automobileEDA.csv`) are kept in their own module folders so nothing overwrites anything else.

## Notes

- Datasets are IBM Skills Network teaching data and are used for academic demonstration only.
- Re-run a notebook with `jupyter notebook` from inside its module folder; the CSVs are referenced with relative paths.
