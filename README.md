# CodSoft Data Science Internship

A collection of machine-learning projects completed during the **CodSoft Data Science Internship**. Each task covers an end-to-end supervised-learning workflow — exploratory data analysis, preprocessing, model training, and evaluation — implemented in Python with scikit-learn.

## Projects

### 1. Titanic Survival Prediction  ·  *Classification*
Predicts whether a passenger survived the Titanic disaster from features such as class, sex, age, family size, fare, and port of embarkation.
- **Workflow:** EDA → drop identifiers → encode categoricals → impute missing values → scale → model.
- **Model:** Logistic Regression
- **Result:** **79.4% accuracy** (81.0% recall, 67.4% precision)
- Notebook: `Titanic_Survival_Prediction.ipynb`

### 2. Sales Price Prediction  ·  *Regression*
Predicts product sales from advertising spend across channels.
- **Workflow:** EDA and correlation analysis → feature selection → model → evaluation.
- **Model:** Linear Regression
- **Result:** **R² = 0.90**
- Notebook: `Sales_Price_Prediction.ipynb`

### 3. Movie Rating Prediction  ·  *Regression*
Predicts a movie's rating from attributes such as genre, director, and cast, comparing several regressors.
- **Workflow:** missing-value analysis (missingno) → feature engineering → train and compare models.
- **Models compared:** Linear Regression, Random Forest, Gradient Boosting
- **Result:** best **R² ≈ 0.71** (Gradient Boosting)
- Notebook: `Movie_Rating_Prediction - Supervised_learning.ipynb`

## Tech stack

Python · pandas · NumPy · scikit-learn · seaborn · matplotlib · missingno · Jupyter Notebook

## Getting started

### 1. Install dependencies

```bash
pip install -r requirements.txt
```

### 2. Launch a notebook

```bash
jupyter notebook
```

Open any of the three notebooks and run the cells top to bottom.

> **Datasets:** the notebooks read their respective CSV datasets (from CodSoft / Kaggle). These are not bundled in the repository — download the corresponding dataset and place it alongside the notebook (or update the file path) before running.

## Project structure

```
Titanic_Survival_Prediction.ipynb              Task 1 — classification
Sales_Price_Prediction.ipynb                   Task 2 — regression
Movie_Rating_Prediction - Supervised_learning.ipynb   Task 3 — regression
requirements.txt                               Python dependencies
```

## Author

**Afnan Ansari** — [github.com/AfnanAnsari748](https://github.com/AfnanAnsari748)
