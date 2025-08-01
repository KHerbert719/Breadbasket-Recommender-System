# Market Basket Analysis with Association Rules

This project performs **market basket analysis** on the `BreadBasket_DMS.csv` 
dataset to discover **association rules** (e.g., “If a customer buys Coffee, they also buy Bread”) 
and generate a **recommender system**.

The output of the model is saved as a CSV file: `association_rules_OUTPUT.csv`

# Dataset Overview

- ***File:** `BreadBasket_DMS.csv`
- **Source:** [Kaggle Dataset](https://www.kaggle.com/datasets/heeraldedhia/breadbasket)
- **Description:** Transactions from a UK-based bakery from 2016–2017.
- **Key Columns:**
  - `Date`: Date of purchase
  - `Time`: Time of purchase
  - `Transaction`: Transaction ID
  - `Item`: Item purchased

# Objective

Use **association rule mining** to identify relationships between products frequently
bought together. This can help:
- Design promotions
- Improve product placement
- Build a simple recommender system
