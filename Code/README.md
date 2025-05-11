# Code Folder – Quick Guide

Two notebooks do all the work:

| Notebook | Goal | Main output |
|-----------|------|-------------|
| **ddavis21_final_project_scraping** | • Scrapes *The Numbers* daily box‑office pages (2017‑2020)<br>• Joins that data with Kaggle movie metadata | `movies_boxoffice_2017_2020_merged.csv` |
| **ddavis21_analysis.ipynb** | • Runs the study’s five questions (elasticities, ANOVA, studio comparison, hit‑vs‑flop model)<br>• Generates every figure used in the final report | PNGs in the `figures/` folder |

**How to run**

1. Open `` and **Run All**  
   *(skip the scrape if the merged CSV already exists).*

2. Open `02_analysis.ipynb` and **Run All**  
   – that recreates all stats and saves the plots.

file 1 can take upwards of 50 minutes to fully scrape

That’s it!
