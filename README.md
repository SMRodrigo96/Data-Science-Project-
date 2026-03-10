# 📊 Data Science Project – Bank Marketing Dataset

## 🔍 Project Overview

This project focuses on applying data science and machine learning techniques to the **Bank Marketing Dataset** from the UCI Machine Learning Repository.  
The main objective is to analyze customer data and build predictive models to determine whether a client is likely to subscribe to a term deposit.

This project is part of my professional portfolio and reflects my training as a **Data Analyst / Junior Data Scientist**, emphasizing data preparation, exploratory analysis, and predictive modeling.

---

## 🎯 Objectives

- Perform data cleaning and preprocessing  
- Conduct exploratory data analysis (EDA)  
- Engineer relevant features  
- Train and evaluate machine learning models  
- Extract insights to support business decision-making  

---

## 📁 Dataset

**Source:** UCI Machine Learning Repository – Bank Marketing Dataset  
https://archive.ics.uci.edu/ml/datasets/Bank+Marketing  

The dataset contains information about bank clients, including demographic, financial, and campaign-related attributes.

---
## 🤖 Machine Learning Models

Two classification models were implemented to predict whether a client would subscribe to a term deposit based on the information collected during marketing campaigns.

### Decision Tree

The Decision Tree model was trained as a baseline classifier to understand the main decision rules of the dataset.

**Advantages**
- Easy to interpret
- Provides clear decision rules

**Limitations**
- Prone to overfitting
- Lower generalization performance compared to ensemble models


### Random Forest

Random Forest was implemented to improve model performance by combining multiple decision trees.

**Advantages**
- Reduces overfitting
- Better generalization
- Handles nonlinear relationships well


---

## 📊 Model Performance

The Random Forest model achieved the following performance metrics:

| Metric | Score |
|------|------|
| Accuracy | 0.89 |
| Precision (Yes) | 0.55 |
| Recall (Yes) | 0.22 |
| ROC AUC | 0.78 |

These results show that the model has a moderate ability to distinguish between clients who will subscribe and those who will not.

---

## 📈 Model Evaluation

The following evaluation techniques were used to assess model performance:

- Confusion Matrix
- ROC Curve
- Model comparison between Decision Tree and Random Forest

---

## 🛠 Technologies

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

---

## 🔬 Methodology

1. Data loading and inspection  
2. Data cleaning and handling missing values  
3. Exploratory Data Analysis (EDA)  
4. Feature engineering  
5. Model training and evaluation  
6. Interpretation of results  

---

## 📊 Results & Insights

- Identified key variables influencing term deposit subscription  
- Built and evaluated classification models  
- Achieved solid performance for a baseline machine learning solution  

*(You can later add specific metrics such as accuracy, precision, recall, or F1-score.)*

---

## 🚀 How to Run the Project

```bash
git clone https://github.com/SMRodrigo96/Data-Science-Project-
cd Data-Science-Project-
pip install -r requirements.txt
jupyter notebook
```

## 📌 Key Learnings

- End-to-end machine learning workflow
- Data preprocessing best practices
- Model evaluation and comparison
- Translating analytical results into business-oriented insights

## 👤 Author

Rodrigo Santa Maria
Aspiring Data Analyst / Junior Data Scientist
