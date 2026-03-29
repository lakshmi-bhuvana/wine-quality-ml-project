# 🍷 Wine Quality Prediction using Machine Learning

## 📌 Project Overview

This project focuses on predicting wine quality using Machine Learning techniques. The dataset contains physicochemical properties of wine, and the objective is to classify wines as **Good** or **Bad** based on their quality score.

---

## 🎯 Objective

* Analyze the Wine Quality dataset
* Perform data preprocessing and feature engineering
* Train and evaluate multiple ML models
* Compare model performance
* Improve results using feature scaling and hyperparameter tuning

---

## 📊 Dataset

* Wine Quality Dataset

* Input features include:

  * Fixed Acidity
  * Volatile Acidity
  * Citric Acid
  * Residual Sugar
  * Chlorides
  * Free Sulfur Dioxide
  * Total Sulfur Dioxide
  * Density
  * pH
  * Sulphates
  * Alcohol

* Target variable:

  * `quality` (original score)

* Created target:

  * `quality_label`

    * **1 (Good)** → Quality ≥ 7
    * **0 (Bad)** → Quality < 7

---

## ⚙️ Workflow

1. Data Loading using Pandas
2. Data Exploration (`head()`, `info()`, `describe()`)
3. Checking Missing Values
4. Correlation Analysis
5. Feature Engineering (Binary Classification)
6. Train-Test Split
7. Model Training:

   * Logistic Regression (before scaling)
   * Logistic Regression (after scaling)
   * K-Nearest Neighbors (KNN)
   * Decision Tree
8. Model Evaluation:

   * Accuracy
   * Precision
   * Recall
   * F1-score
   * Confusion Matrix
9. Hyperparameter Tuning using GridSearchCV
10. Feature Importance Analysis

---

## 🤖 Models Used

* Logistic Regression
* K-Nearest Neighbors (KNN)
* Decision Tree Classifier

---

## 📈 Results

* Feature scaling improved Logistic Regression performance
* KNN and Decision Tree performed better due to their ability to capture non-linear relationships
* Important features influencing wine quality:

  * Alcohol
  * Sulphates
  * Volatile Acidity

---

## 🛠️ Tech Stack

* Python
* NumPy
* Pandas
* Scikit-learn
* Matplotlib
* Seaborn

---

## 📊 Project Structure

wine-quality-ml-project/
│
├── wine_quality_prediction.ipynb
├── winequality.csv
├── README.md

---

## 📌 Conclusion

This project demonstrates the importance of preprocessing, feature scaling, and model selection in Machine Learning. It also highlights how different algorithms perform on the same dataset and how tuning improves model performance.

---

## 🚀 Future Improvements

* Use advanced models like Random Forest or XGBoost
* Perform deeper feature engineering
* Deploy the model using a web application

---

## 👤 Author

Lakshmi Bhuvana Durvasula


