# Credit Card Fraud Detection Using Machine Learning

A Jupyter Notebook project comparing Logistic Regression and Random Forest for detecting fraudulent credit-card transactions.

## Dataset
Download `creditcard.csv` from the Kaggle dataset:
https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

Place the file at `Dataset/creditcard.csv`. The dataset is intentionally not included in this repository ZIP because it is large and has its own Kaggle distribution page.

## Setup
```bash
python -m pip install -r requirements.txt
jupyter notebook
```

Open `Credit_Card_Fraud_Detection.ipynb` and run all cells from top to bottom.

## Project contents
- `Credit_Card_Fraud_Detection.ipynb` — complete workflow, training, evaluation, charts and example prediction
- `Dataset/` — place the downloaded CSV here
- `models/` — saved models and scaler (created after running notebook)
- `outputs/` — generated charts and model comparison (created after running notebook)

## Methods
- Logistic Regression with class weighting
- Random Forest with class weighting
- Stratified 80/20 train-test split
- Standardization of `Time` and `Amount`
- Accuracy, precision, recall, F1-score, ROC-AUC and PR-AUC

**Note:** This is an academic demonstration, not a production-ready financial fraud detection service.
