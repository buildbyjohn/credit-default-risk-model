# Credit Default Risk Model

Predicting the probability that a borrower will default on a loan, using statistics and machine learning.

## Goal

Build an end-to-end credit risk model that combines:

- **Math**: probability, statistics, logistic regression, model evaluation
- **Data science / AI**: data cleaning, feature engineering, machine learning
- **Finance**: probability of default (PD), credit scoring, risk-based decisions

## Project Status

- [ ] Set up repo and environment
- [ ] Get and explore the dataset (EDA)
- [ ] Clean data and engineer features
- [ ] Baseline model: logistic regression
- [ ] Better model: random forest / gradient boosting
- [ ] Evaluate (ROC-AUC, precision/recall, confusion matrix)
- [ ] Interpret results (which features drive default risk?)
- [ ] Write up findings

## Dataset

To be decided (candidates: Lending Club, German Credit, Give Me Some Credit on Kaggle).

## Project Structure

```
credit-default-risk-model/
├── data/           # raw and processed data (not committed if large)
├── notebooks/      # Jupyter notebooks for exploration and modelling
├── src/            # reusable Python code
├── README.md
├── requirements.txt
└── .gitignore
```

## Setup

```bash
git clone https://github.com/<your-username>/credit-default-risk-model.git
cd credit-default-risk-model
python -m venv venv
venv\Scripts\activate        # Windows
pip install -r requirements.txt
```

## Tools

Python, pandas, NumPy, scikit-learn, matplotlib, Jupyter, Git/GitHub

## Author

John, first-year Mathematics student.
