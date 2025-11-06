# Introvert-Extrovert Classification

A machine learning project to classify individuals as **Introvert** or **Extrovert** using behavioral and social activity data. Implemented with **Random Forest** and **XGBoost** models. Based on the Kaggle competition: [Playground Series S5E7](https://www.kaggle.com/c/playground-series-s5e7).

---

## Project Overview
This project aims to **build predictive models that classify individuals as Introvert or Extrovert** based on behavioral and social activity features. It demonstrates the complete machine learning workflow from data preprocessing to model evaluation and comparison.

---

## Dataset
The dataset is provided by Kaggle for this competition and contains features such as:

- Time spent alone  
- Social event attendance  
- Stage fear  
- Friends circle size  
- Post frequency  
- Other behavioral and social indicators  

The dataset files include:

- `train.csv` — training data for model development  
- `test.csv` — test data for generating competition submissions  

---

## Features & Engineering
Key engineered features include:

- **Alone_to_Social_Ratio** — ratio of time spent alone to social event attendance  
- **Energy_Drain_Index** — energy drain after socializing  
- **Social_Activity_Score** — combined social activity metric  
- **Confidence_Index** — social confidence relative to stage fear  
- **Total_Engagement** — total engagement across social activities  

These features help highlight behavioral patterns distinguishing introverts from extroverts.

---

## Models Used
- **Random Forest Classifier** — robust ensemble method for classification  
- **XGBoost Classifier** — gradient boosting method with high predictive performance  

The workflow includes:

1. Data cleaning and missing value imputation  
2. Encoding categorical variables  
3. Feature engineering  
4. Exploratory Data Analysis (EDA)  
5. Scaling numeric features  
6. Outlier detection and removal  
7. Model training, validation, and performance comparison  

---

## Results
- Both Random Forest and XGBoost models were evaluated on the validation set.  
- Random Forest slightly outperformed XGBoost in terms of AUC and overall metrics.  
- The final predictions are generated using the best-performing model.  

---

## Repository
All project files, including the **Jupyter Notebook** with step-by-step implementation, are available in this repository: `<your-repo-url>`.  

---

## References
- Kaggle Competition: [Playground Series S5E7](https://www.kaggle.com/c/playground-series-s5e7)
- Scikit-learn: [https://scikit-learn.org](https://scikit-learn.org)
- XGBoost Documentation: [https://xgboost.readthedocs.io](https://xgboost.readthedocs.io)
