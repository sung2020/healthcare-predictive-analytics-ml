Healthcare Predictive Analytics

This project uses EDA and machine learning on three healthcare datasets to study diabetes screening, life expectancy prediction, and hospital mortality risk.

Files
healthcare_predictive_analytics_capstone_report.pdf — final report
notebooks/eda/ — data cleaning and EDA notebooks
notebooks/modeling/ — modeling and evaluation notebooks
results/ — confusion matrix results

Main Findings
The diabetes dataset had class imbalance, especially for prediabetes. SMOTE did not improve prediabetes prediction.

Life expectancy was strongly related to education, income, adult mortality, and HIV/AIDS-related variables.

The SUPPORT2 hospital mortality model performed strongly using clinical and survival-related features.

Data Note
The raw datasets are not included. The notebooks were run locally using public healthcare datasets, and saved outputs are included for review.

Tools
Python, Jupyter Notebook, pandas, numpy, matplotlib, seaborn, scikit-learn, imbalanced-learn, and openpyxl.

Project Note
This project was completed as part of my data science coursework and is included here as a portfolio project.
