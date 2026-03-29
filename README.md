# 🍷 Wine Quality Prediction using Machine Learning

## 📌 Project Overview

This project predicts wine quality using Machine Learning techniques. Based on various physicochemical properties, the model classifies wine as **Good** or **Bad**.

---

## 🎯 Objective

* Perform data analysis on the Wine Quality dataset
* Build and evaluate multiple ML models
* Compare model performance
* Improve accuracy using feature scaling and hyperparameter tuning

---

## 📊 Dataset

The dataset contains chemical properties of wine such as:

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

### 🎯 Target Variable

* `quality` → original score
* `quality_label` → created column

  * **1 (Good)** → Quality ≥ 7
  * **0 (Bad)** → Quality < 7

---

## ⚙️ Workflow

1. Data Loading and Exploration (`head()`, `info()`, `describe()`)
2. Checking Missing Values
3. Correlation Analysis
4. Feature Engineering (Binary Target Creation)
5. Train-Test Split
6. Model Training:

   * Logistic Regression (without scaling)
   * Logistic Regression (with scaling)
   * K-Nearest Neighbors (KNN)
   * Decision Tree
7. Model Evaluation:

   * Accuracy
   * Precision
   * Recall
   * F1-score
   * Confusion Matrix
8. Hyperparameter Tuning using GridSearchCV
9. Feature Importance Analysis

---

## 🤖 Models Used

* Logistic Regression
* K-Nearest Neighbors (KNN)
* Decision Tree Classifier

---

## 📈 Results

* Feature scaling improved Logistic Regression performance
* KNN and Decision Tree performed better due to non-linear relationships
* Key features affecting wine quality:

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

## 📁 Project Structure

wine-quality-ml-project/
│
├── wine_quality_prediction.ipynb
├── winequality.csv
├── README.md

---

## 📥 How to Clone and Run the Project

### 🔹 Clone Repository

```bash
git clone https://github.com/lakshmi-bhuvana/wine-quality-ml-project.git
```

### 🔹 Navigate to Folder

```bash
cd wine-quality-ml-project
```

### 🔹 Install Dependencies

```bash
pip install numpy pandas scikit-learn matplotlib seaborn
```

### 🔹 Run the Project

#### Option 1: Jupyter Notebook

```bash
jupyter notebook
```

Open:

```
wine_quality_prediction.ipynb
```

#### Option 2: Google Colab

* Open Google Colab
* Upload notebook file
* Upload dataset
* Run all cells

---

## 📊 Output

* Model performance metrics (Accuracy, Precision, Recall, F1-score)
* Confusion Matrix
* Feature Importance graph

---

## 📌 Conclusion

This project highlights the importance of data preprocessing, feature scaling, and model selection in Machine Learning. It also demonstrates how different algorithms perform on the same dataset.

---

## 🚀 Future Improvements

* Use advanced models like Random Forest or XGBoost
* Perform deeper feature engineering
* Deploy the model as a web application

---

## 👤 Author

Lakshmi Bhuvana Durvasula
