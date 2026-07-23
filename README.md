# 🚢 Titanic Survival Prediction using Logistic Regression

A Machine Learning classification project that predicts whether a passenger survived the Titanic disaster based on passenger information. This project demonstrates the complete machine learning workflow, including data preprocessing, exploratory data analysis (EDA), feature engineering, model building, and evaluation using Logistic Regression.

---

## 📌 Project Overview

The objective of this project is to build a binary classification model that predicts passenger survival on the Titanic dataset.

Target Variable:
- **Survived**
  - 0 → Did Not Survive
  - 1 → Survived

---

## 📂 Dataset

The dataset contains passenger details such as:

- Passenger Class (Pclass)
- Sex
- Age
- Fare
- Number of Siblings/Spouses (SibSp)
- Number of Parents/Children (Parch)
- Embarked Port
- Cabin
- Passenger Name

---

## 🔍 Exploratory Data Analysis (EDA)

Performed detailed exploratory data analysis including:

- Missing value analysis
- Distribution of numerical features
- Survival rate comparison
- Correlation analysis
- Survival by gender
- Survival by passenger class
- Survival by family size
- Feature relationship visualizations using Seaborn and Matplotlib

---

## ⚙️ Feature Engineering

Created a new feature:

```python
Family Size = SibSp + Parch + 1
```

This feature represents the total number of family members traveling together, including the passenger.

---

## 🛠️ Data Preprocessing

- Handled missing values
- Encoded categorical variables
- Selected relevant features
- Train-Test Split

---

## 🤖 Machine Learning Model

**Algorithm Used**

- Logistic Regression

---

## 📊 Model Evaluation

Evaluation metrics used:

- Accuracy Score
- Confusion Matrix
- Classification Report
  - Precision
  - Recall
  - F1-Score

### 📈 Model Performance

| Metric | Value |
|---------|--------|
| Accuracy | **79.8%** |

---

## 🧰 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

---

## 📁 Project Structure

```

```

---

## 🚀 Key Learning Outcomes

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Data Visualization
- Logistic Regression
- Binary Classification
- Model Evaluation
- Machine Learning Workflow

---

## 📌 Future Improvements

- Feature Scaling
- ROC Curve & AUC Score
- Cross Validation
- Hyperparameter Tuning
- Compare Multiple Classification Models
- Deploy using Streamlit

---

## 👩‍💻 Author

**Palak Mallik**

GitHub: https://github.com/PalakMallik

LinkedIn: https://www.linkedin.com/in/palak-mallik/

---

⭐ If you found this project useful, consider giving it a star!
