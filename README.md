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
- EasyEnsembleClassifier
**Evaluation Metrics:**
- Precision, Recall, F1-Score
- ROC-AUC
- Confusion Matrix  
**Includes:**
- Class balancing undersampling and oversampling
- SHAP analysis for explainability

### 3. `SecureBank Fraud Detection System_streamlit.ipynb`
**Purpose:**  
Implements a **Streamlit-based interactive dashboard** to demonstrate fraud classifications.  
**Features:**
- Upload transactions for classification
- Visual feedback on fraud probability
- Integrated with final trained model

## 📦 Data Source

Dataset used: [Credit Card Fraud Detection (Kaggle)](https://www.kaggle.com/datasets/kartik2112/fraud-detection)  
Files:  
- `fraudTrain.csv.zip`  
- `fraudTest.csv.zip`  

Please unzip and place them in the working directory to run the notebooks successfully.

## 🧪 Setup Instructions
- git clone the repository
- Add .pkl file of the model you want for the detection
- Install dependencies are in the notebooks
- From https://www.kaggle.com/datasets/kartik2112/fraud-detection/data download the two dataset: train and test
- Upload the test file + .pkl file to run the streamlit notebook 


