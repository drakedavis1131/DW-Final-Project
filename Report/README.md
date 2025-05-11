# U.S. Wide‑Release Box‑Office Drivers (2017 – 2020)

**Author:** _\<Drake Davis\>_  
**Course:** BAIS 3500 – Data Wrangling  
**Report:** `Data Wrangling Project Report.docx` (see `reports/`)

---

## 1  Project Overview
This project explores what drives *opening‑day* box‑office revenue for wide‑release movies in the United States (2017‑2020).  
Key questions:

1. Does screen count truly buy more dollars?  
2. Do larger production budgets guarantee bigger debuts?  
3. Does holiday timing boost per‑screen returns?  
4. Which major studio squeezes the most from each theater?  
5. Can we classify “hits” vs. “flops” before release?

---

## 2  Data Sources
| Source | File | Notes |
|--------|------|-------|
| **The Numbers** daily grosses | `daily_boxoffice_2017_2020.csv` | 21 k rows scraped with Selenium. |
| **Kaggle Movies Metadata** | `movies_metadata.csv` | Budget, runtime, release date. |
| **Merged dataset** | `movies_boxoffice_2017_2020_merged.csv` | 303 wide releases, joined on title + year. |

---


---

## 3 Key Findings
* **Screens ≈ 1 : 1 revenue elasticity** – 10 % more screens ⇒ ~10 % more opening‑day gross.  
* **Budgets show diminishing returns** – elasticity ≈ 0.8.  
* **No holiday per‑screen premium** – Welch‑ANOVA p ≈ 0.27.  
* **Disney dominates per‑screen earnings** – ~$2.7 k vs. ~$1.5 k for rivals.  
* **Random‑forest classifier** predicts top‑quartile “hits” with 78 % accuracy (ROC AUC 0.82).

---


