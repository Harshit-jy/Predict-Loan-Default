# 💸 Loan Default Prediction Using Machine Learning

This project uses machine learning to predict whether a borrower will default on a loan based on their financial history and credit information. The model is trained using a dataset provided by the user and includes a complete classification pipeline with evaluation and visualization.

---

## 📌 Project Overview

Loan default prediction is critical for banks and financial institutions to minimize risk. Using historical loan data, we train a **Logistic Regression** model to classify borrowers as likely to default (`1`) or not (`0`). This repository includes data preprocessing, model training, evaluation metrics, and visualization (confusion matrix heatmap).

---

## 📂 Files Included

- `loan_default_prediction.py`: Main Python script that loads a CSV file, trains a model, and outputs metrics.
- `README.md`: Project documentation.
- (Optional) `requirements.txt`: Python dependencies for the project.

---

## 🧠 Features

- Accepts **custom user dataset** (CSV file)
- Supports **categorical and numerical features**
- **One-hot encoding** for categorical variables
- **Feature scaling** for model optimization
- Trains a **Logistic Regression** model
- Outputs **accuracy, precision, recall**
- Generates a **confusion matrix heatmap**

---

## 🛠️ How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/loan-default-prediction.git
cd loan-default-prediction
