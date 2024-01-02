

# SP901 Capstone Project

   This capstone project focuses on SP901 Machine Learning applied to medical data, specifically addressing the binary classification of a PET dataset. Various methods, including Logistic Regression, K-Nearest Neighbors (KNN), Support Vector Machine (SVM), Random Forest (RF), and XGBOOST, are employed for the classification task. The effectiveness of each method is evaluated through the assessment of ROC-AUC and F1-score, ultimately aiming to determine the most optimal method for the given dataset.
   
# 5.3 Final Project


## 5.3.1 Python for Data Science and Machine Learning

Guidelines:
1. Using the dataset provided, create a binary classification
2. Perform the following:
    *  Perform an exploratory analysis (scaling, PCA, unbalanced)
    *  Split the data (train, validation, test)
    *  Perform 10-fold cross-validation and grid search (method of your choice)
    *  Compare the different classification methods
        (Logistic Regression, KNN, SVM, RF, XGBOOST)
    *  Show evaluation metrics (ROC-AUC, accuracy, f-1 score)
    *  Submit the jupyter notebook

### Procedure

- **1. Data Preprocessing:** Managing missing data and removal of outliers
- **2. Data Imbalances:**  Using SMOTE for handling imbalances
- **3. Data Scaling:** Scaling data using StandardScaler from SKlearn
- **4. Feature Selection:** Feature selection using RFE from SKlearn with Logistic Regression as the based model
- **5. Split Data:** Split data for training, validation and testing
- **6. Binary Classification:** Classification using Logistic Regression, K-Nearest Neighbors (KNN), Support Vector Machine (SVM), Random Forest (RF), and XGBOOST algorithms
- **7. Best Model Selection:** Evaluating the best model through ROC-AUC and F1 Scoring
