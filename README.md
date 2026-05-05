# Vertebral Column Anomaly Classifier

Data Science project implementing a pipeline to classify vertebral columns as "normal" or "abnormal" using Machine Learning techniques.

## Overview
This repository aims to experiment with preprocessing, exploratory data analysis, feature engineering and classification models to identify normal/abnormal cases in vertebral column data. The focus is reproducibility and clarity of the workflow (notebooks, scripts and reports).

## Data
Each record contains clinical attributes and a label indicating normality/abnormality.

G. Barreto and A. Neto. "Vertebral Column," UCI Machine Learning Repository, 2005. [Online]. Available: https://doi.org/10.24432/C5K89B.

## Modeling and evaluation
- Model considered: XGBoost.
- Metrics: accuracy, precision, recall, f1-score and confusion matrix.
- Validation: k-fold cross-validation.

## How to run (example)
1. Create environment:
   - python -m venv env
   - source env/bin/activate (Linux/macOS) or env\Scripts\activate (Windows)
2. Install dependencies:
   - pip install -r requirements.txt
3. Run notebooks:
   - jupyter lab

## Expected results
- Experiment report with the selected best model.
- Serialized model artifact and evaluation metrics.
- Feature importance visualizations and confusion matrix.

## Contribution
- Open issues for bugs or improvements.
- Send PRs with small changes and tests/documentation.

## Contact
For questions or collaborations, open an issue in this repository.
