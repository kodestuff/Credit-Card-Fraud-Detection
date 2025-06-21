#Credit Card Fraud Detection Project

A machine learning project to detect fraudulent credit card transactions using Python, pandas, and scikit-learn. Built with a real-world imbalanced dataset and trained using SMOTE + Random Forest.

---

## 📁 Files Included

- `CC_fraud_detection.ipynb`: Complete code in Python (Google Colab)
- `creditcard.csv`: Dataset (from Kaggle)
- `requirements.txt`: All dependencies
- `.gitignore`: Avoid tracking temporary files

---

## 📌 Problem Statement

The objective is to detect fraud transactions from anonymized credit card data. The dataset is highly imbalanced (fraud cases ≈ 0.17%).

---

## ⚙️ Tools and Libraries

- Python (Google Colab)
- pandas, numpy
- seaborn, matplotlib
- scikit-learn
- imbalanced-learn (SMOTE)

---

## 🧪 Project Steps

1. **Data Exploration**: Checking nulls, types, class distribution.
2. **Data Visualization**: Countplots, boxplots, correlation heatmap.
3. **Data Preprocessing**: Scaling, dropping unnecessary columns.
4. **Handling Imbalance**: Using SMOTE to balance training data.
5. **Model Training**: Random Forest Classifier.
6. **Evaluation**: Classification report, confusion matrix, ROC curve.

---

## 🔍 Model Results

| Metric        | Value     |
|---------------|-----------|
| Accuracy      | ~99.9%    |
| Precision     | 95% (fraud) |
| Recall        | 95% (fraud) |
| ROC AUC       | 0.97      |

---

## 📊 ROC Curve

![ROC Curve Example](https://upload.wikimedia.org/wikipedia/commons/1/13/Roc_curve.svg)

## How to Run This Project

1. Clone this repo:
   ```bash
   git clone https://github.com/kodestuff/CC_Fraud_Detection.git
   cd CC_Fraud_Detection
Create virtual environment (optional but recommended)


python -m venv venv
source venv/bin/activate  # on Windows use venv\\Scripts\\activate
Install dependencies:

pip install -r requirements.txt
Run the notebook:

jupyter notebook CC_fraud_detection.ipynb

