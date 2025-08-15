# 🩺 Liver Disease Classification using Machine Learning

## 📌 Project Overview
This project aims to predict whether a patient has liver disease based on clinical and biochemical features using multiple machine learning models.  
The dataset was analyzed, preprocessed, and evaluated using various algorithms to identify the best-performing model.

---

## 📊 Dataset
- **Source:** Indian Liver Patient Dataset (ILPD)
- **Rows:** 583
- **Target Variable:** `Dataset` (1 = Liver Disease, 0 = No Liver Disease)
- **Features:**
  - Age
  - Gender
  - Total_Bilirubin
  - Direct_Bilirubin
  - Alkaline_Phosphotase
  - Alamine_Aminotransferase
  - Aspartate_Aminotransferase
  - Total_Protiens
  - Albumin
  - Albumin_and_Globulin_Ratio

---

## 🛠 Steps Performed
1. **Exploratory Data Analysis (EDA)**
   - Checked data distribution & null values
   - Visualized correlations between features
   - Analyzed class imbalance

2. **Data Preprocessing**
   - Handling missing values
   - Encoding categorical variables (Gender)
   - Feature scaling using `StandardScaler`
   - Splitting dataset into train & test sets

3. **Model Training**
   - **Logistic Regression**
   - **K-Nearest Neighbors (KNN)**
   - **Support Vector Machine (SVM)**
   - **Decision Tree Classifier**
   - Hyperparameter tuning using GridSearchCV

4. **Evaluation**
   - Accuracy
   - Precision, Recall, F1-score
   - Confusion Matrix

---

## 📈 Model Performance

| Model | Train Accuracy | Test Accuracy | Notes |
|-------|---------------|--------------|-------|
| Logistic Regression | 71.17% | **76.99%** | Best generalization |
| KNN | 71.17% | 66.37% | Lower performance |
| SVM (Tuned) | 71.17% | 71.68% | Predicts all as class 1 |
| Decision Tree | 100% | 63.71% | Overfits badly |

---

📬 Future Improvements

Apply SMOTE or class weighting to handle imbalance

Try Random Forest and XGBoost

Use AUC-ROC for better evaluation

---



🖋 Author

SANIYA CHHABRA
