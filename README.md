# Fraud Detection with Autoencoders + XGBoost

## Overview
Unsupervised pretraining med autoencoder för att extrahera features på transaktioner, därefter XGBoost för klassificering av fraud vs non-fraud.

## Data
- Dataset: `creditcard.csv` (ladda ner från https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud?resource=download , placera därefter i `data/creditcard.csv`)
- **Obs:** Stora dataset är exkluderade från repo.

## Env
```bash
python -m venv .venv && source .venv/bin/activate
pip install -r requirements.txt
