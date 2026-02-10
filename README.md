# 🚢 Titanic Survival Prediction — EDA & Machine Learning

A comprehensive Data Science project focused on **Exploratory Data Analysis (EDA)** and **Predictive Modeling** using the Titanic dataset. This project demonstrates a complete workflow from raw data cleaning to achieving a high-accuracy classification model.

## 📦 Dataset Overview
The dataset provides insights into the demographics and survival outcomes of Titanic passengers.
* **Target:** `Survived` (0 = No, 1 = Yes)
* **Key Features:** `Pclass`, `Sex`, `Age`, `Fare`, `Embarked`
* **Source:** Kaggle Titanic Dataset

## 🎯 Objectives
* Conduct a **Missingness Audit** to diagnose and treat null values.
* Perform **EDA** to uncover survival trends among different passenger groups.
* Implement **Feature Engineering** (Label Encoding & Feature Selection).
* Develop a **Random Forest Classifier** to predict survival probability.

## ⚙️ Environment & Tools
* **Python** 3.10+
* **Libraries:** `pandas`, `seaborn`, `matplotlib`, `scikit-learn`
* **Platform:** Jupyter Notebook / Google Colab

## 🔎 Data Cleaning Strategy
A professional approach was used to ensure data integrity:
* **Imputation:** Handled `Age` gaps using **Median** and `Embarked` using **Mode**.
* **Feature Selection:** Dropped `Cabin` due to >70% missingness and removed non-predictive columns like `Name` and `Ticket`.

## 🧠 Model & Performance
The project utilizes the **Random Forest** algorithm, known for its robustness and accuracy in classification tasks.
* **Algorithm:** Random Forest Classifier (100 estimators)
* **Validation Split:** 80% Training, 20% Testing
* **Final Accuracy:** **81.01%**

## 📈 Key Insights
* **Gender Bias:** Female passengers had a significantly higher survival rate.
* **Class Impact:** Passengers in **1st Class** had priority access to lifeboats, resulting in higher survival probability.
* **Age Factor:** Younger passengers (children) showed higher survival rates due to evacuation policies.

## 🚀 How to Use
1. Clone the repository.
2. Ensure `train.csv` and `test.csv` are in the root directory.
3. Run `(EDA)_&_Visualizations.ipynb` to view full analysis and predictions.

## 📝 License
This project is licensed under the **MIT License**.
