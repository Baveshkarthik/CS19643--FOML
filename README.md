# Breast Cancer Detection using Machine Learning

## 📌 Project Title
Breast Cancer Prediction using Logistic Regression

---

## 🧠 Algorithm Used
- Logistic Regression

Logistic Regression is a supervised machine learning algorithm used for binary classification problems. It predicts whether the output belongs to one of two categories (Malignant or Benign) using probability.

---

## 📊 Dataset
- Breast Cancer Wisconsin Dataset (from sklearn)
- Total samples: 569
- Features: 30 medical attributes

### Target Classes:
- 0 → Malignant (Cancerous)
- 1 → Benign (Non-cancerous)

---

## 🔢 Train-Test Split
- Training Data: 80% → 455 samples
- Testing Data: 20% → 114 samples

The model is trained on training data and evaluated on unseen testing data.

---

## ⚙️ Methodology

1. Load dataset using sklearn
2. Convert data into DataFrame
3. Visualize data using countplot
4. Split data into training and testing sets
5. Apply feature scaling using StandardScaler
6. Train model using Logistic Regression
7. Predict results on test data
8. Evaluate model using accuracy and confusion matrix

---

## 📈 Accuracy Calculation

Accuracy is calculated using:

Accuracy = (Correct Predictions / Total Predictions) × 100

In this project:
- Correct Predictions = 111
- Total Predictions = 114

Accuracy ≈ 97.37%

---

## 📊 Graph Explanation

### Target Distribution Graph
- Shows number of malignant and benign cases
- Helps understand dataset balance
- More benign cases than malignant

---

## 📉 Confusion Matrix Explanation

|                | Predicted Malignant | Predicted Benign |
|----------------|--------------------|------------------|
| Actual Malignant | 41 | 2 |
| Actual Benign    | 1  | 70 |

### Meaning:
- 41 → Correct malignant predictions
- 70 → Correct benign predictions
- 2 → Malignant predicted as benign (error)
- 1 → Benign predicted as malignant (error)

---

## 🎯 Use of Algorithm

- Helps classify tumors automatically
- Reduces manual diagnosis effort
- Assists doctors in decision-making

---

## 🏥 Applications

- Medical diagnosis
- Early cancer detection
- Healthcare data analysis

