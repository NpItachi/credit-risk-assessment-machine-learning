# UCI Credit Risk Assessment

This project focuses on assessing credit risk using the UCI Credit Card Default dataset. It implements three machine learning models—**Logistic Regression**, **Random Forest**, and **XGBoost**—to predict the likelihood of credit default based on customer features. Exploratory Data Analysis (EDA), data preprocessing, and model evaluation are included.

---

## 📊 Dataset

- **Name**: Default of Credit Card Clients Dataset  
- **Source**: [Kaggle - UCI Credit Card Dataset](https://www.kaggle.com/datasets/uciml/default-of-credit-card-clients-dataset)  
- **Records**: 30,000 credit card clients  
- **Features**: Demographic, credit, billing, and payment information  
- **Target Variable**: `default.payment.next.month` (1 = Defaulted, 0 = Not Defaulted)

---

## 🧠 Project Objectives

- Perform exploratory data analysis (EDA) on the UCI credit dataset.
- Clean and preprocess the data (including encoding and scaling).
- Handle class imbalance using **SMOTE**.
- Train and evaluate the following ML models:
  - Logistic Regression
  - Random Forest
  - XGBoost
- Visualize model performance using confusion matrices and ROC curves.

---

## 🛠️ Technologies Used

- Python 3
- Pandas, NumPy
- Scikit-learn
- Seaborn, Matplotlib
- Imbalanced-learn (SMOTE)
- XGBoost

---


## 📈 Evaluation Metrics

Each model is evaluated using:

- Accuracy
- ROC-AUC Score
- Precision, Recall, F1-score
- Confusion Matrix
- ROC Curve

---

## 📊 Results Snapshot

| Model               | Accuracy | ROC-AUC |
|--------------------|----------|---------|
| Logistic Regression| 0.69     | 0.69    |
| Random Forest       | 0.79     | 0.74   |
| XGBoost             | 0.76     | 0.73    |

---

## 🧪 Future Improvements

- Hyperparameter tuning for all models
- Feature selection/engineering
- Comparison with additional algorithms (e.g., SVM, LightGBM)
- Model deployment with Flask or Streamlit

---

## 📜 License

This project is for educational and research purposes. Dataset is publicly available via the UCI repository on Kaggle.

---

## 🙋‍♂️ Author

**Nilesh Pawar**

If you find this project helpful, feel free to ⭐ star the repository!


