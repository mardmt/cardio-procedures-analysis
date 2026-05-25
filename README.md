# Cardio Procedures Analysis

## Overview
Exploratory data analysis and machine learning risk prediction on the Heart Failure Clinical Records dataset (299 patients, 13 clinical variables). This project demonstrates the application of data science and predictive modelling techniques to clinical cardiovascular data.

## Dataset
- **Source:** Heart Failure Clinical Records Dataset (Kaggle)
- **Patients:** 299
- **Variables:** 13 clinical features including age, ejection fraction, serum creatinine, and death event
- **Mortality rate:** 32.1%

## Project Structure
```
cardio-procedures-analysis/
│
├── 01_data_exploration.ipynb       # Exploratory analysis and visualizations
├── 02_forecasting.ipynb            # Predictive modelling and model comparison
├── 03_ai_clinical_report.ipynb     # Automated clinical report generation
├── heart_failure_clinical_records_dataset.csv
└── README.md
```

## Key Findings
- Peak mortality risk window: 50-70 years of age
- Serum creatinine is the strongest single predictor of death
- Lower ejection fraction strongly associated with mortality
- Random Forest outperforms Logistic Regression (72% vs 65% accuracy)

## Tools Used
- Python, Pandas, Matplotlib, Scikit-learn
- Jupyter Notebook
- GitHub

## Limitations
- Small dataset (299 patients) limits model generalizability
- 44% of deaths still missed by best model
- External validation required before any clinical application
```
