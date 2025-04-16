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





# 🛍️ Online Shopping & Book Dataset Analysisμ GREEK VERSION

Αυτό το project συνδυάζει την ανάλυση δεδομένων από **online shoppers** και **best-selling books** με σκοπό να εξερευνήσει πρότυπα συμπεριφοράς, να εφαρμόσει clustering και να εκπαιδεύσει μοντέλα μηχανικής μάθησης για πρόβλεψη και κατηγοριοποίηση.

---

## 📌 Περιγραφή Έργου

📈 Ανάλυση του **Online Shoppers Intention Dataset**  
📚 Ανάλυση του **Amazon Top 50 Bestselling Books (2009–2021)**  
🎯 Στόχος: Κατανόηση και πρόβλεψη της αγοραστικής πρόθεσης / ποιότητας βιβλίων

---

## 🧰 Τεχνολογίες

- **Python 3.x**
- **Βιβλιοθήκες**: `pandas`, `numpy`, `matplotlib`, `seaborn`, `plotly`, `scikit-learn`, `xgboost`, `shap`
- **Οπτικοποίηση**: `plotly`, `seaborn`, `matplotlib`
- **ML**: Random Forest, XGBoost, SVM
- **Ερμηνεία Μοντέλων**: SHAP
- **Clustering**: KMeans
- **Dashboards**: Plotly Dash *(προαιρετικά)*

---

## 🔍 Pipeline Ανάλυσης

1. **Data Preprocessing**  
   Καθαρισμός, encoding, μετασχηματισμοί

2. **Exploratory Data Analysis (EDA)**  
   Γραφήματα, στατιστικά, συσχετίσεις

3. **Clustering**  
   Ανίχνευση ομάδων επισκεπτών ή βιβλίων

4. **Μηχανική Μάθηση**  
   Προβλέψεις για Revenue ή Rating

5. **Model Explainability**  
   SHAP values για κατανόηση αποτελεσμάτων

6. **Time Series Analysis** *(για Books)*  
   Ανάλυση πωλήσεων ανά έτος

---

## 📊 Dataset Links

- 
- 📚 [Top 50 Bestselling Novels (2009–2021)(]https://www.kaggle.com/datasets/zwl1234/top-50-bestselling-novels-20092021-of-amazon)

---

## ▶️ Εκτέλεση

```python
# Φόρτωση δεδομένων
df = pd.read_csv('/kaggle/input/online-shoppers-intention/online_shoppers_intention.csv')
books = pd.read_csv('/kaggle/input/top-50-bestselling-novels-20092021-of-amazon/...')
