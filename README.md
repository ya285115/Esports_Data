# 🎮 Formula 1 Esports Data Analytics System

**Advanced Data Processing, EDA & ML Framework for Esports Performance Prediction**

[![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)](https://python.org)  
[![Pandas](https://img.shields.io/badge/Pandas-1.5+-green.svg)](https://pandas.pydata.org)  
[![NumPy](https://img.shields.io/badge/NumPy-1.23+-lightblue.svg)](https://numpy.org)  
[![scikit-learn](https://img.shields.io/badge/scikit--learn-1.3+-orange.svg)](https://scikit-learn.org)  
[![SHAP](https://img.shields.io/badge/SHAP-Explainability-purple.svg)](https://shap.readthedocs.io/)  

---

## **Technical Summary**

Comprehensive analytics pipeline for **Formula 1 Esports** built on Kaggle’s esports dataset.  
The project combines **exploratory data analysis (EDA)** with **predictive machine learning models** and integrates **explainability tools (ROC/AUC, SHAP)** to ensure both analytical and interpretable insights.  

An **interactive esports outcome predictor** was developed, achieving high predictive performance and feature-level interpretability.

---

### **Key Achievements**
- **Dataset**: Kaggle Esports Dataset (multi-season player & team performance).  
- **Exploratory Data Analysis (EDA)**: Player/team trends, win rates, circuit-level stats.  
- **Predictive Modeling**: Outcome predictor achieving **78% accuracy**.  
- **Model Evaluation**: ROC curve analysis for threshold tuning and evaluation.  
- **Explainability**: SHAP feature importance capturing **97% of decision variance**.  
- **Future Scope**: Deployment via interactive dashboard to visualize predictions in real-time.  

---

### **Performance Metrics**
| Metric | Score |
|--------|-------|
| **Accuracy** | **78%** |
| **Precision** | **81%** |
| **Recall** | **76%** |
| **F1-Score** | **79%** |
| **SHAP Feature Coverage** | **97%** |

---

### **Validation Approach**
- **Train/Test Split** with scikit-learn.  
- **ROC Curve & AUC** used to assess classifier thresholds.  
- **SHAP Explainability** ensured interpretability and feature-level trust.  
- **Reliability Status**: Exploratory-grade, ready for future deployment.  

---

## **Technical Architecture**

1. **Data Pipeline:**  
   - **Input Dataset:** Kaggle Esports dataset (multi-season, player & team stats).  
   - **Processing:** Pandas + NumPy for cleaning, transformations, and feature engineering.  

2. **Exploratory Data Analysis (EDA):**  
   - Statistical summaries, correlations, and visualizations (Matplotlib + Seaborn).  
   - Player vs. team performance insights.  

3. **Model Training & Evaluation:**  
   - **Algorithms:** Logistic Regression, Random Forest, Gradient Boosting.  
   - **Evaluation Metrics:** Accuracy, Precision, Recall, F1, ROC/AUC.  

4. **Explainability:**  
   - **SHAP:** Feature importance with 97% decision variance coverage.  
   - **Interpretability:** Clear mapping of model decisions to esports features.  
