# Eurostat Visual Study

This repository contains a notebook-based visual analysis of Eurostat asylum application data (2013–2022), including preprocessing, trend analysis, and clustering.

## Final Report

The main deliverable is available here:

- [report.pdf](./report.pdf)

## Project Structure

- `1_preprocessing.ipynb` – data loading, cleaning, and preparation
- `2_decade_shift.ipynb` – decade-level trend and shift analysis
- `3_intake_impact.ipynb` – analysis of intake-related impacts
- `4_clustering_multivals.ipynb` – multi-variable clustering exploration
- `report.pdf` – final write-up of methods, visuals, and findings
- `requirements.txt` – Python dependencies

## Data Source

Eurostat table: `migr_asyappctza`  
https://ec.europa.eu/eurostat/databrowser/view/migr_asyappctza/default/table?lang=en&category=migr.migr_asy.migr_asyapp

## Setup

1. Create and activate a Python environment.
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open and run the notebooks in order (`1_` to `4_`).
