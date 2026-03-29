This folder supplements the paper
“Feature Engineering Matters: Machine Learning in Chinese Stock Return Prediction — Evidence from Fundamental Signals.”

The purpose of this repository is to provide the core Python codes used for data preprocessing, feature engineering, machine learning model training, portfolio construction, and empirical evaluation in the paper.

The following Python scripts are included in this folder:
1.Machine Learning Strategy.py
This script implements the core machine learning pipeline used in the paper, including:
  (1)Data cleaning and alignment at the firm–month level
  (2)Construction of 100 fundamental signals and selection of 30 fundamental signals using the random forest algorithm on the full sample
  (3)Training machine learning models using 30 fundamental signals and 100 fundamental signals respectively(LightGBM model)
  (4)Risk-Adjusted Performance for 100-signal and 30-signal LightGBM strategy under four factor models (CAPM,Fama3,Fama5, Fama5+MOM)
  (5)Cross-sectional Test of Full-set Signals on Large-cap and Small-cap Portfolios
  (6)Subsample Period Performance Comparison
  (7)Top 10 Signal Importance Horizontal Bar Chart
  (8)Strategy Performance Comparison Bar Chart

2.Recursive Ranking Strategy.py
This script implements the recursive ranking strategy pipeline used in the paper, including:
  30-signal and 100-signal recursive ranking strategy