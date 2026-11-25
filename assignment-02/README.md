# Assignment 02 — Data Visualization with Python

Coursework for **CISC7204 – Data Science and Data Visualization** (University of Macau). This assignment progresses from static Matplotlib charts and geospatial maps to interactive Plotly and Dash dashboards. Notebooks are based on the IBM *Data Visualization with Python* labs.

> Only the core deliverables are kept here: `.ipynb` notebooks, `.py` Dash scripts, `.json` map data, `.png` report figures, and the project proposal `.docx`. Web-page caches (`*_files`), `.html` exports, `.DS_Store`, `._*` metadata and `.ipynb_checkpoints` were removed. Original filenames are preserved.

## Modules

| Folder | Topic | What it covers |
| --- | --- | --- |
| `Module 01/` | Pandas & Matplotlib Basics | Exploring and pre-processing a dataset with Pandas; introduction to Matplotlib and line plots. |
| `Module 02/` | Chart Types | Area plots, histograms, bar charts, pie charts, box plots, scatter and bubble plots; plotting directly with Matplotlib. |
| `Module 03/` | Advanced & Geospatial | Waffle charts, word clouds and regression plots; creating maps and visualising geospatial data (`world_countries.json`). |
| `Module 04/` | Plotly & Dash | Basic Plotly charts; Dash basics, interactivity, bar-plot callbacks, and flight-delay / flight-detail dashboard scripts. |
| `Module 05/` | Final Assignment | Automobile-sales recession analysis with Matplotlib / Seaborn / Folium, plus the interactive Dash sales dashboard and its two report figures. A wildfire-analysis practice assignment is included too. |

## Notes on the large notebook

The **Module 04 Lab01** notebook (*Basic Plotly Charts*) originally contained embedded Plotly JSON and base64 PNG outputs and was about **31.7 MB**. Its cell outputs and execution counts were cleared (all 102 cells, 39 code cells and 63 markdown cells, and every line of code retained), reducing it to well under 5 MB. Run the notebook to regenerate the charts.

## Relationship to the main project

The final deliverables of `Module 05/` are the source of the automotive-sales project in the repository root: `01_automobile_sales_eda.ipynb`, `02_sales_dashboard.py`, `recession_report.png` and `yearly_report.png`. Those root files are cleaned-up, renamed copies; this folder keeps the original coursework for reference.

## Notes

- Datasets and GeoJSON files are fetched at runtime from IBM Skills Network URLs or read from the local `.json` files; teaching data is used for academic demonstration only.
- Dash scripts are standalone: run `python <script>.py` and open `http://127.0.0.1:8050`.
