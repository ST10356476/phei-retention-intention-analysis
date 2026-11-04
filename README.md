# Determinants of Student Retention Intention at a Private Higher Education Institution in South Africa

Quantitative analysis for my Postgraduate Diploma in Data Analytics research report (The Independent Institute of Education, 2026).

## Overview
This study examines how **institutional factors**, **academic engagement** and **student satisfaction** relate to students' **retention intention** at a registered private higher education institution in Gauteng. Data came from a cross-sectional online survey (n = 119). The notebook runs all of the analysis in Python.

## Key findings
- The three predictors together explain **21.7%** of the variance in retention intention.
- **Student satisfaction** is the only significant unique predictor (β = .51), and this held across all robustness checks.
- Institutional factors and satisfaction are highly correlated (r = .81) and could not be separated statistically.
- Retention intention did not differ significantly by demographic group, but satisfaction was lower among senior students.


## How to run
1. Install the dependencies: `pip install -r requirements.txt`
2. Place the survey export (`.xlsx`) in `data/` (see `data/README.md`).
3. Open the notebook in `notebooks/` and choose **Run All**.

## Methods
Reliability analysis (Cronbach's α, McDonald's ω), exploratory factor analysis with parallel analysis, Pearson and Spearman correlations, OLS multiple regression with diagnostics, HC3 robust standard errors and bootstrap confidence intervals, dominance analysis, and group comparisons (Welch t-test, ANOVA, Kruskal–Wallis).

## Data and ethics
The raw survey data is **not included**. Participation was anonymous and voluntary, and the data is held only by the researcher in line with the study's ethical clearance and POPIA.

## Author
Phalanndwa Delron Munyai (ST10356476) · Supervisor: Ms L Njokwe