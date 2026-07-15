# Customer Churn Prediction

A Machine Learning project that predicts whether a telecom customer is likely to churn based on customer demographics, account information, and service usage. The project includes data preprocessing, exploratory data analysis (EDA), model training, evaluation, hyperparameter tuning, and model serialization for future deployment.

---

## Project Overview

Customer churn is one of the biggest challenges faced by subscription-based businesses. Identifying customers who are likely to leave helps companies take proactive measures to improve customer retention.

In this project, multiple machine learning algorithms are trained and compared to predict customer churn. The best-performing model is further optimized using hyperparameter tuning.

---

## Dataset

**Dataset:** Telco Customer Churn Dataset

The dataset contains customer information such as:

* Customer demographics
* Account details
* Services subscribed
* Monthly charges
* Total charges
* Contract type
* Payment method
* Churn status (Target Variable)

**Target Variable**

* **Churn**

  * Yes → Customer left the company
  * No → Customer stayed

---

## Project Workflow

1. Load the dataset
2. Perform data inspection
3. Handle missing values
4. Perform Exploratory Data Analysis (EDA)
5. Encode categorical features
6. Scale numerical features
7. Handle class imbalance using SMOTE
8. Train multiple machine learning models
9. Compare models using Cross Validation
10. Tune the best model using RandomizedSearchCV
11. Evaluate model performance
12. Save the trained model using Pickle

---

## Exploratory Data Analysis

EDA includes:

* Dataset overview
* Missing value analysis
* Duplicate value check
* Numerical feature distributions
* Boxplots for outlier detection
* Correlation heatmap
* Categorical feature analysis
* Churn distribution visualization

---

## Models Used

* Decision Tree Classifier
* Random Forest Classifier
* XGBoost Classifier

Model comparison was performed using **5-Fold Cross Validation**.

---

## Techniques Used

* Label Encoding
* Standard Scaling
* SMOTE (Synthetic Minority Oversampling Technique)
* Cross Validation
* RandomizedSearchCV
* Model Serialization using Pickle

---

## Libraries Used

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* XGBoost
* imbalanced-learn
* Pickle

---

## Model Evaluation

The models were evaluated using:

* Accuracy Score
* Confusion Matrix
* Classification Report
* Cross Validation Score

The best-performing model was further optimized using **RandomizedSearchCV**.

---

## Files

```
Customer_Churn_Prediction.ipynb   # Complete notebook
customer_churn_pred.pkl           # Saved trained model
requirements.txt                  # Project dependencies
README.md                         # Project documentation
```

---

## How to Run

1. Clone the repository

```bash
git clone https://github.com/your-username/Customer-Churn-Prediction.git
```

2. Navigate to the project directory

```bash
cd Customer-Churn-Prediction
```

3. Install the required packages

```bash
pip install -r requirements.txt
```

4. Open the notebook

```bash
jupyter notebook Customer_Churn_Prediction.ipynb
```

---

## Future Improvements

* Deploy the model using Streamlit or Flask
* Perform feature selection
* Add ROC Curve and AUC Score comparison
* Improve hyperparameter tuning
* Build a customer churn prediction web application

---

## Author

**Sandhya Joshi**

If you found this project helpful, consider giving the repository a ⭐.

