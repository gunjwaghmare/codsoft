# codsoft
Projects for CodSoft Machine Learning Internship
# 💳 Credit Card Fraud Detection
This project is a part of my **Machine Learning Internship** at [CodSoft](https://www.codsoft.in). The objective is to detect fraudulent credit card transactions using supervised machine learning techniques.

---

## 📁 Dataset
- Source: [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/datasets/kartik2112/fraud-detection)
- Contains anonymized features representing transaction characteristics.
- Target variable: `is_fraud` (0 = legitimate, 1 = fraud)

---

## 📌 Problem Statement
Build and evaluate a classification model that can accurately detect fraudulent transactions based on various transaction features.

---

## ⚙️ Tools & Libraries Used
- Python
- pandas, NumPy, matplotlib, seaborn
- scikit-learn (Logistic Regression, Random Forest)
- Jupyter Notebook (in VS Code)

---

## 🧪 ML Workflow
1. **Data Exploration & Cleaning**
   - Dropped unnecessary or high-cardinality columns
   - Handled categorical features with one-hot encoding

2. **Feature Scaling**
   - Applied `MinMaxScaler` to normalize input data

3. **Modeling**
   - Logistic Regression
   - Random Forest Classifier

4. **Evaluation**
   - Accuracy Score
   - Confusion Matrix
   - Classification Report
   - ROC-AUC Curve

---

## 🎯 Results
- **Random Forest** performed better in both accuracy and recall compared to Logistic Regression.
- Achieved high performance in identifying fraudulent transactions despite dataset imbalance.

---

## 📦 How to Run
```bash
pip install -r requirements.txt

