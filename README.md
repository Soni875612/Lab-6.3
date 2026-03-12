## Lab Activity 6.3 — Dimensionality Reduction Using PCA on IT Job Market Data
Objective
To apply Principal Component Analysis (PCA) for dimensionality reduction on an IT job market dataset in India — simplifying high-dimensional data while preserving critical information to enable better analysis of factors influencing high-paid IT roles.
Dataset
🔗 Position Salary Dataset — Kaggle
Requirements

Python (Jupyter Notebook / Google Colab)
Libraries: pandas, numpy, scikit-learn, matplotlib, seaborn

Prerequisites

Basic Python knowledge
Understanding of feature scaling and preprocessing techniques
Basic understanding of PCA and its applications
Knowledge of data visualization using Matplotlib/Seaborn

Problem Statement
The Indian IT job market is highly competitive, with many factors influencing salaries — experience, skills, company, and location. Analyzing this high-dimensional dataset is challenging. PCA reduces dimensionality while retaining important variance, helping identify key components that drive higher salaries and enabling visualization and trend analysis.
Steps
StepTask1Import required libraries2Load the dataset3Data preprocessing — handle missing values, scale features4Apply PCA to reduce dimensions5Visualize PCA components (scatter plot of principal components)6Interpret variance explained by each component and draw conclusions
Key Concept — PCA
TermMeaningPrincipal ComponentsNew axes that capture maximum variance in dataExplained Variance RatioHow much information each component retainsDimensionality ReductionReducing number of features while keeping key patterns
Tech Stack
LibraryUsagepandasData loading and manipulationnumpyNumerical operationsscikit-learnPCA, StandardScaler, preprocessingmatplotlib / seabornPCA component visualization
File Structure
Lab6_3/
├── Lab6_3.ipynb                  # Main notebook
├── position_salary_dataset.csv   # Dataset
└── README.md                     # This file
Conclusion
PCA successfully reduces the dimensionality of the IT job market dataset while retaining most of the variance. Analyzing the principal components reveals patterns among high-paid IT roles in India, supporting strategic decisions for job seekers, recruiters, and HR analytics.
