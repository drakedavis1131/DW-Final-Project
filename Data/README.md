# Data Folder README

<h1 style="font-size:2.2em; color:red;"> IMPORTANT: READ THE OTHER README FILE AS WELL. THERE IS ONE MISSING FILE FROM KAGGLE! </h1>


This folder holds the CSV files used (and produced) by the notebooks.

| File | What it is | Rows | Notes |
|------|------------|------|-------|
| **`movies_metadata.csv`** | Raw Kaggle file from Banik (2017) – budgets, runtimes, release dates. | 45 k+ | Unedited download. |
| **`daily_boxoffice_2017_2020.csv`** | Raw scrape of *The Numbers* daily charts (Jan 2017 – Dec 2020). | 21 196 | One row per title × calendar date. |
| **`movies_boxoffice_2017_2020_merged.csv`** | Clean, merged data set used in analysis. | 303 | One row per wide‑release title (first appearance), joins the two sources. |


