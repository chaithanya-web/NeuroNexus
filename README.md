# 🚢 Titanic Survival Prediction

A beginner-friendly machine learning project using the Titanic dataset to predict whether a passenger survived or not based on features like age, gender, class, fare, and more.

---

## 📌 Overview

This project uses the classic Titanic dataset to build a classification model that predicts passenger survival. It includes data preprocessing, feature engineering, model training using a Random Forest Classifier, and evaluation through accuracy score and visualizations.

---

## 🧠 Goal

Predict whether a passenger survived the Titanic disaster using machine learning based on features such as:
- Passenger Class (Pclass)
- Sex
- Age
- Fare
- Family aboard (SibSp & Parch)
- Embarkation port

---

## 📊 Dataset

The dataset contains the following columns:

| Column        | Description                                       |
|---------------|---------------------------------------------------|
| PassengerId   | Unique ID for each passenger                      |
| Survived      | Target variable (0 = No, 1 = Yes)                 |
| Pclass        | Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd)          |
| Name          | Full name of passenger                            |
| Sex           | Gender (male/female)                              |
| Age           | Age in years                                      |
| SibSp         | # of siblings/spouses aboard                      |
| Parch         | # of parents/children aboard                      |
| Ticket        | Ticket number                                     |
| Fare          | Fare paid                                         |
| Cabin         | Cabin number                                      |
| Embarked      | Port of Embarkation (C = Cherbourg, Q = Queenstown, S = Southampton) |

---

## 🛠️ Technologies Used

- Python
- Pandas
- Scikit-learn
- Seaborn & Matplotlib

---

## 🧼 Data Preprocessing

- Dropped irrelevant columns (`Name`, `Ticket`, `Cabin`, `PassengerId`)
- Filled missing values in `Age` with median and `Embarked` with mode
- Converted categorical columns (`Sex`, `Embarked`) to numeric using Label Encoding

---

## 🤖 Model Training

- Model Used: **Random Forest Classifier**
- Evaluation Metric: **Accuracy Score**
- Train-Test Split: 80% training, 20% testing

---

## 📈 Visualizations

The project includes the following visualizations to understand the data better:

- Survival Count
- Survival by Gender
- Survival by Passenger Class
- Age Distribution
- Embarked Port vs Survival
- Correlation Heatmap

---

## 🚀 How to Run the Project

### 1. Clone the repository
```bash
git clone https://github.com/yourusername/titanic-survival-prediction.git
cd titanic-survival-prediction
