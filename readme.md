# 🧠 Predicting Liver Cirrhosis using Machine Learning

This project focuses on **early prediction of liver cirrhosis** using multiple machine learning algorithms. The goal is to help healthcare providers take timely and personalized actions using clinical data.

---

## 📌 Problem Statement

Liver cirrhosis is a chronic liver disease marked by irreversible scarring. If undetected early, it can result in life-threatening complications. This project builds ML models that classify whether a person is at risk of liver cirrhosis based on medical features.


---

## 📊 Dataset

- **Source:** [Kaggle - Indian Liver Patient Dataset](https://www.kaggle.com/datasets/uciml/indian-liver-patient-records)
- **Instances:** 583
- **Features:** 10 medical attributes + 1 target
- **Target Values:**
  - 1 → Liver disease
  - 0 → No liver disease

---

## 🧪 Models Used

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Random Forest
- XGBoost

### 🔍 Evaluation Metrics:
- Accuracy
- Precision
- Recall
- F1 Score

---

## 🔬 Model Performance

| Model               | Accuracy | Precision | Recall | F1 Score |
|--------------------|----------|-----------|--------|----------|
| Random Forest       | **0.82** | **0.84**  | **0.85** | **0.84** |
| XGBoost             | 0.76     | 0.78      | 0.83   | 0.80     |
| Logistic Regression | 0.72     | 0.73      | 0.75   | 0.74     |
| KNN                 | 0.70     | 0.68      | 0.72   | 0.70     |

✅ **Random Forest (tuned)** performed best after hyperparameter tuning.

---

## 🛠 Technologies Used

- Python 3
- Jupyter Notebook
- Pandas, NumPy, Matplotlib, Seaborn
- Scikit-learn, XGBoost

---

## 🚀 How to Run

```bash
# Clone this repository
git clone https://github.com/gaddevinay/Predicting-Liver-Cirrhosis-using-ML.git
cd Predicting-Liver-Cirrhosis-using-ML

# Open Jupyter Notebook
jupyter notebook

# Run notebooks in this order:
# 1. dataset_preparation.ipynb
# 2. descriptive_statistical.ipynb
# 3. visual_analysis.ipynb
# 4. train_multiple_models.ipynb
# 5. hyperparameter_tuning_rf.ipynb
```

---

## 📦 Future Improvements

- [ ] Deploy the best model using Flask or Streamlit
- [ ] Add cross-validation for more reliable performance
- [ ] Record a short demo video of the model in action

---

