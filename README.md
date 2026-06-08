## View Full Notebook
👉 [Click here to view the full analysis](https://nbviewer.org/github/apoorvaayyagari/Global-Cancer-Analysis/blob/main/Global_Cancer_Analysis.ipynb)
Global Cancer Patient Analysis
Overview
This project explores 50,000 global cancer patient records from Kaggle (2015–2024) using Python. The goal was to understand what factors most strongly influence cancer severity and treatment costs — and whether any of those patterns hold up statistically.
Key Findings

Smoking and Genetic Risk are the two strongest predictors of cancer severity, both showing a correlation of around 0.48 — nearly equal in influence
Age has almost no relationship with severity, which challenges the common assumption that older patients automatically have more severe cancer
None of the measured risk factors significantly predict how long a patient survives — suggesting survival is more dependent on treatment quality and access to care than pre-existing risk
Cancer stage does not significantly affect treatment cost or survival duration — a finding that surprised me and points to the dataset capturing something more nuanced than simple staging
Genetic Risk and Smoking do not interact in a statistically significant way — they appear to contribute to severity independently rather than amplifying each other

Techniques Used

Descriptive statistics and distribution analysis
Pearson and Spearman correlation analysis
KDE plots, histograms, heatmaps and bar charts
Kruskal-Wallis hypothesis testing
OLS regression with interaction terms
Random Forest Regressor with GridSearchCV hyperparameter tuning

Tools and Libraries

Python — Pandas, NumPy
Visualisation — Matplotlib, Seaborn
Statistics — Scipy
Machine Learning — Scikit-learn, Statsmodels

Dataset
Global Cancer Patients 2015–2024
Source: Kaggle
50,000 patient records across 15 features
Author
Apoorva Ayyagari
GitHub — LinkedIn
