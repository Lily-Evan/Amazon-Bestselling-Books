# 🛍️ Online Shopping & Book Dataset Analysis

This project combines analysis of **Online Shoppers Intention** and **Amazon's Top 50 Bestselling Books (2009–2021)** datasets to uncover behavioral insights, apply clustering, and train machine learning models for prediction and classification.

---

## 📌 Project Overview

📈 Analysis of the **Online Shoppers Intention Dataset**  
📚 Analysis of the **Amazon Bestselling Books Dataset**  
🎯 Goal: Understand and predict purchasing intent / book rating patterns

---

## 🧰 Technologies Used

- **Python 3.x**
- **Libraries**: `pandas`, `numpy`, `matplotlib`, `seaborn`, `plotly`, `scikit-learn`, `xgboost`, `shap`
- **Visualization**: `plotly`, `seaborn`, `matplotlib`
- **Machine Learning**: Random Forest, XGBoost, SVM
- **Explainability**: SHAP
- **Clustering**: KMeans
- **Dashboards**: Plotly Dash *(optional)*

---

## 🔍 Analysis Pipeline

1. **Data Preprocessing**  
   Cleaning, encoding, transformations

2. **Exploratory Data Analysis (EDA)**  
   Visualizations, statistics, correlations

3. **Clustering**  
   Identify user/book segments with KMeans

4. **Machine Learning Models**  
   Predict `Revenue` or `Rating` classes

5. **Model Explainability**  
   SHAP values to interpret feature importance

6. **Time Series Analysis** *(Books Dataset)*  
   Analyze trends in book sales over years

---

## 📊 Dataset Sources

- 
- 📚 [Amazon Top 50 Bestselling Novels (2009–2021)](https://www.kaggle.com/datasets/zwl1234/top-50-bestselling-novels-20092021-of-amazon)

---

## ▶️ Getting Started

```python
# Load dataset
df = pd.read_csv('/kaggle/input/online-shoppers-intention/online_shoppers_intention.csv')
books = pd.read_csv('/kaggle/input/top-50-bestselling-novels-20092021-of-amazon/...')






## ▶️ Εκτέλεση

```python
# Φόρτωση δεδομένων
df = pd.read_csv('/kaggle/input/online-shoppers-intention/online_shoppers_intention.csv')
books = pd.read_csv('/kaggle/input/top-50-bestselling-novels-20092021-of-amazon/...')
