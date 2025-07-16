#Heart Disease Prediction Using Logistic Regression

This project uses a machine learning model to predict the presence of heart disease in patients based on several medical attributes. It’s a clean, beginner-friendly end-to-end implementation of data exploration, visualization, preprocessing, and classification using logistic regression.

---

## 📁 Dataset

The dataset `heart.csv` contains 13 features and 1 target variable indicating heart disease presence (1) or absence (0).

---

## 🔍 Features Description

| Feature | Description |
|--------|-------------|
| age | Age in years |
| sex | 1: Male, 0: Female |
| cp | Chest pain type (1–4) |
| trestbps | Resting blood pressure |
| chol | Serum cholesterol (mg/dl) |
| fbs | Fasting blood sugar > 120 mg/dl (1 = true; 0 = false) |
| restecg | Resting ECG results (0, 1, 2) |
| thalach | Maximum heart rate achieved |
| exang | Exercise-induced angina (1 = yes; 0 = no) |
| oldpeak | ST depression induced by exercise |
| slope | Slope of the peak exercise ST segment |
| ca | Number of major vessels colored by fluoroscopy (0–3) |
| thal | 3 = normal; 6 = fixed defect; 7 = reversible defect |

---

## 📊 Visualizations

- Target class distribution (`sns.countplot`)
- Feature correlation heatmap (`sns.heatmap`)

---

## 🛠️ Model & Tools Used

- **Model**: Logistic Regression (`sklearn.linear_model`)
- **Preprocessing**: `StandardScaler`
- **Train/Test Split**: 80/20 (`train_test_split`)
- **Evaluation Metrics**: Accuracy, Confusion Matrix, Classification Report

---

## ✅ Results

```text
Accuracy: 0.85

Confusion Matrix:
[[25  4]
 [ 5 27]]

Classification Report:
              precision    recall  f1-score   support
           0       0.83      0.86      0.85        29
           1       0.87      0.84      0.86        32

    accuracy                           0.85        61
   macro avg       0.85      0.85      0.85        61
weighted avg       0.85      0.85      0.85        61
