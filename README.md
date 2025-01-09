# Credit Card Fraud Detection Model  

This project implements a machine learning model to detect fraudulent credit card transactions. The model leverages **SMOTE (Synthetic Minority Oversampling Technique)** for handling class imbalance, employs a **Random Forest Classifier** for classification, and optimizes hyperparameters using **GridSearchCV**. The final model achieves **89% precision** and **93% balanced accuracy**.  

---

## Features  
- **Fraud Detection**: Accurately identifies fraudulent transactions while minimizing false positives.  
- **Imbalanced Data Handling**: Utilizes SMOTE to address the imbalance between fraudulent and legitimate transactions.  
- **Hyperparameter Optimization**: Employs GridSearchCV to tune Random Forest hyperparameters for optimal performance.  
- **Performance Metrics**: Reports precision, recall, balanced accuracy, and other metrics to evaluate model efficacy.  

---

## Dataset  
The dataset contains anonymized credit card transaction data, including features derived from PCA. Fraudulent transactions account for a small fraction of the data.  
https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud/data

---

## Methodology  

1. **Data Preprocessing**:  
   - Standardized the data to ensure features are on a comparable scale.  
   - Split the data into training and testing sets.  

2. **Addressing Class Imbalance**:  
   - Applied **SMOTE** to oversample the minority class (fraudulent transactions).  

3. **Model Selection**:  
   - Chose **Random Forest Classifier** for its robustness and ability to handle complex datasets.  

4. **Hyperparameter Tuning**:  
   - Used **GridSearchCV** to find the best combination of hyperparameters, including the number of estimators, max depth, and min samples split.  

5. **Performance Evaluation**:  
   - Evaluated the model using metrics like **precision**, **recall**, **F1-score**, and **balanced accuracy**.  

---

## Results  
- **Precision**: 89%  
- **Balanced Accuracy**: 93%  

The high precision ensures that the model minimizes false positives, which is critical in fraud detection. Balanced accuracy confirms the model performs well on both classes despite the dataset's imbalance.  

---

## Requirements  

To run the project, you will need:  

- Python 3.8+  
- Libraries:  
  - `numpy`  
  - `pandas`  
  - `scikit-learn`  
  - `imbalanced-learn`  
  - `matplotlib` (optional for visualizations)  


