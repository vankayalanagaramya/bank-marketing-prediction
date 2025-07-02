# Predicting Bank Marketing Campaign Results

This project aims to predict whether a client will subscribe to a bank’s term deposit product based on direct marketing campaign data. It was completed as part of a graduate-level course at NJIT.

## 📊 Dataset
- Source: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Bank+Marketing)
- 41,188 records, 21 attributes
- Target variable: `y` (yes/no for term deposit subscription)

## 🧠 Models Used
- XGBoost
- Random Forest
- Decision Tree
- K-Nearest Neighbors (KNN)
- 1D Convolutional Neural Network (Conv1D)

## ⚙️ Techniques
- Data preprocessing (normalization, encoding)
- Handling class imbalance using **SMOTEENN**
- Hyperparameter tuning via grid search
- Evaluation using accuracy, precision, recall, F1, AUC-ROC

## 📈 Results (AUC Scores)
| Model        | AUC  |
|--------------|------|
| Random Forest| 0.89 |
| XGBoost      | 0.88 |
| Conv1D NN    | 0.86 |
| Decision Tree| 0.86 |
| KNN          | 0.80 |

## 📂 Files
- `bank_marketing_prediction.ipynb`: Jupyter notebook with all code
- `project_report.pdf`: Final project report with methodology and results
- `requirements.txt`: Python libraries used




