# 🚢 Titanic – Machine Learning from Disaster

This project is part of my **Kaggle Experiments** series and explores the famous Kaggle competition:

🔗 https://www.kaggle.com/competitions/titanic

The objective is to build a **machine learning model that predicts whether a passenger survived the Titanic disaster** using passenger information such as age, gender, ticket class, and fare.

---

## 📌 Overview

The sinking of the **RMS Titanic in 1912** is one of the most well-known maritime disasters.  
In this competition, we analyze passenger data and build a predictive model to answer:

> **What kinds of passengers were more likely to survive?**

Using historical passenger data, we apply **data analysis, feature engineering, and machine learning techniques** to predict survival outcomes. :contentReference[oaicite:1]{index=1}

---

## 📂 Dataset

The dataset provided by Kaggle contains passenger information from the Titanic voyage.

### Files

| File | Description |
|-----|-------------|
| `train.csv` | Training dataset with survival labels |
| `test.csv` | Test dataset without survival labels |
| `gender_submission.csv` | Example submission format |

### Important Features

- **PassengerId** – Unique identifier
- **Survived** – Target variable (0 = No, 1 = Yes)
- **Pclass** – Passenger class (1st, 2nd, 3rd)
- **Name** – Passenger name
- **Sex** – Gender
- **Age** – Passenger age
- **SibSp** – Siblings / spouses aboard
- **Parch** – Parents / children aboard
- **Ticket** – Ticket number
- **Fare** – Ticket price
- **Cabin** – Cabin number
- **Embarked** – Port of embarkation

---

## ⚙️ Project Workflow

### 1️⃣ Data Loading
- Import dataset using **Pandas**
- Inspect structure and missing values

### 2️⃣ Exploratory Data Analysis (EDA)
- Survival distribution
- Gender vs survival
- Passenger class impact
- Age distribution analysis

### 3️⃣ Data Preprocessing
- Handle missing values
- Encode categorical variables
- Feature selection

### 4️⃣ Model Building
Machine learning algorithms are used to predict passenger survival.

Possible models:
- Logistic Regression
- Decision Tree
- Random Forest

### 5️⃣ Prediction
- Train model using training dataset
- Generate predictions for test dataset
- Create Kaggle submission file

---

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 📁 Repository Structure
```
Titanic - Machine Learning from Disaster/
│
├── Titanic.ipynb
├── train.csv
├── test.csv
├── submission.csv
└── README.md
```
---

## 📊 Goal

The goal of this project is to:

- Practice **data analysis and feature engineering**
- Apply **machine learning models on real-world data**
- Generate predictions for the Kaggle competition leaderboard

---

## 🚀 Future Improvements

- Advanced feature engineering
- Hyperparameter tuning
- Ensemble models
- Gradient Boosting / XGBoost

---

## 📚 Acknowledgement

Dataset and competition provided by **Kaggle**.
