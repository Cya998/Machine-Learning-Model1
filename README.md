# Machine-Learning-Model1: SDG 10 Machine Learning Project

This project explores Sustainable Development Goal 10: Reduce Inequality using machine learning. The goal is to analyze global trends in GDP, Gini Index, poverty, and unemployment to identify countries at risk of high inequality and predict future inequality levels.

The project uses a two-step ML approach:

Unsupervised Learning (K-Means Clustering), which groups countries into clusters based on inequality indicators (High, Medium, Low).

Supervised Learning (Random Forest Regressor), which predicts future Gini Index levels and provides insight into potential inequality trends for each country.

Data:

Global datasets (2005–2024) for GDP per capita, Gini Index, Poverty Headcount, and unemployment levels.

Data is cleaned, interpolated, and normalized to manage missing values and ensure consistent comparisons across countries.

Key Features:

Identifies clusters of countries with different inequality levels.

Predicts future inequality using Random Forest regression.

Includes visualizations of clusters and trends at the country level.

Ethical Considerations:

Data-driven insights aim to support policymakers and researchers.

The project emphasizes responsible use of predictions and acknowledges the social and economic complexities behind the numbers.

Usage:

Open the Jupyter notebook (pooks.ipynb) to explore the workflow.

Run cells in order to reproduce the steps for data cleaning, clustering, regression, and visualization.
