# 🛡️ Credit Card Fraud Detection using Machine Learning

This repository contains a machine learning project designed to detect fraudulent credit card transactions using a large and imbalanced dataset. The project was developed as part of my university-level machine learning course and focuses on practical data preprocessing, model building, and evaluation techniques.

## 📊 Dataset

- **Source**: [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/datasets/kartik2112/fraud-detection)
- **Files**: `fraudTrain.csv`, `fraudTest.csv`
- **Size**: 1,852,394 rows, 23 columns
- **Note**: Data was synthetically generated to simulate real-world transactions.

## ⚙️ Features

- Dropped irrelevant columns (e.g., names)
- Label-encoded categorical variables
- Standardized numeric features for model compatibility
- Applied **SMOTE** to handle severe class imbalance

## 🤖 Models

### Baseline Model
- **Model**: Decision Tree Classifier
- **Purpose**: Quick testing of preprocessing pipeline
- **Limitations**: Shallow depth (max_leaf_nodes = 5), limited performance

### Advanced Model
- **Model**: Random Forest Classifier
- **Evaluation**: Achieved ~65% accuracy after applying SMOTE

## 📈 Evaluation

- Used **MSE** and **precision-recall curves** during early stages
- Plan to implement:
  - **F1 Score**
  - **ROC AUC**
  - **Confusion Matrix**

## 🚀 Future Improvements

- Hyperparameter tuning (GridSearchCV)
- Dimensionality reduction (PCA)
- Implement binary classifier neural network
- Use better evaluation metrics suited for imbalanced classification

## 🧪 Technologies Used

- Python
- Jupyter Notebook
- Pandas, NumPy, Matplotlib
- Scikit-learn
- Imbalanced-learn

## 📝 Authors

- Dylan Hall  
- Galavardino Sousa  
- Brandon Luu

## 📂 Structure

```
.
├── CreditCardFraudProjectFinalSubmission.ipynb
├── CreditCardFraudProjectFinalSubmission.html
├── README.md
```

## 📬 Contact

For questions or feedback, feel free to reach out via GitHub Issues or LinkedIn.
