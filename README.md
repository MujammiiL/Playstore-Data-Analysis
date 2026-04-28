# Google Play Store Data Analysis
 
An end-to-end exploratory data analysis of the Google Play Store — uncovering patterns in app ratings, installs, pricing, and categories using Python.
 
---
 
## Files
 
| File | Description |
|---|---|
| `Playstore_Data_Analysis.ipynb` | Main analysis notebook |
| `Playstore_Cleaned.csv` | Cleaned dataset |
 
---
 
## Dataset Overview
 
~10,837 apps · 33 categories · 119 genres · 11 features including Rating, Installs, Type, Price, Content Rating, and Android Version.
Source:(https://www.kaggle.com/datasets/lava18/google-play-store-apps)
 
---
 
## Workflow
 
**Data Cleaning** — Stripped symbols from `Installs`, `Price`, and `Size`; parsed dates; filled missing values with median/mode; dropped 700 duplicates.
 
**EDA & Statistics** — Filtering, grouping, and descriptive stats (mean, median, mode) across all numerical and categorical columns.
 
**Visualization** — Histograms, KDE plots, bar plots, box plots, scatter plots, heatmaps, and pie charts using `matplotlib` and `seaborn`.
 
---
 
## Key Insights
 
- **~93% of apps are free** — free apps get significantly more installs than paid ones
- **Rating ≠ Installs** — brand and visibility matter more than a perfect rating
- **Reviews & Installs are strongly correlated** — the strongest relationship in the dataset
- **FAMILY** is the most competitive category; **Tools** leads in genre count
- **Median beats mean** for Installs, Reviews, and Price due to extreme outliers
- Most apps target **Android 4.1+** — prioritising reach over cutting-edge features
---
 
## Stack
 
`Python` · `Pandas` · `NumPy` · `Matplotlib` · `Seaborn` · `Jupyter Notebook`
 

 
**Mujammil** · B.Sc. Mathematics · Data Analytics Certified  
[GitHub](https://github.com/your-username) · [LinkedIn](https://linkedin.com/in/your-profile)
