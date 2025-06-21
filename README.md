# 🛡️ Credit Card Fraud Detection - CRISP-DM Project

This repository contains a complete data science pipeline to detect fraudulent credit card transactions using machine learning techniques, developed according to the **CRISP-DM** (Cross-Industry Standard Process for Data Mining) framework.

## 📁 Repository Contents

This project includes the following Jupyter notebooks:

### 1. `EDA.ipynb`
**Purpose:**  
Conducts extensive **Exploratory Data Analysis** on the `fraudTrain.csv` and `fraudTest.csv` datasets.  
**Highlights:**
- Distribution analysis of numerical and categorical features
- Detection of extreme class imbalance
- Temporal and behavioral insights
- Visualizations for key fraud patterns

### 2. `Models & Evaluations.ipynb`
**Purpose:**  
Performs **feature engineering**, model training, and evaluation on the processed dataset.  
**Models Used:**
- Random Forest
- XGBoost
- LightGBM
- Logistic Regression  
**Evaluation Metrics:**
- Precision, Recall, F1-Score
- ROC-AUC
- Confusion Matrix  
**Includes:**
- Class balancing with SMOTE
- SHAP analysis for interpretability

### 3. `SecureBank Fraud Detection System_streamlit.ipynb`
**Purpose:**  
Implements a **Streamlit-based interactive dashboard** to demonstrate fraud predictions.  
**Features:**
- Upload transactions for prediction
- Visual feedback on fraud probability
- Integrated with final trained model

## 📦 Data Source

Dataset used: [Credit Card Fraud Detection (Kaggle)](https://www.kaggle.com/datasets/kartik2112/fraud-detection)  
Files:  
- `fraudTrain.csv.zip`  
- `fraudTest.csv.zip`  

Please unzip and place them in the working directory to run the notebooks successfully.

## 🧪 Setup Instructions

```bash

# git clone the repository

# Install dependencies are in the notebooks

# In the streamlit app you will need to adjust the model you want for the detection
