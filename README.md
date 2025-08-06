# Project-Customer-Churn-
This project uses the Telco Customer Churn dataset available on Kaggle. The main goal is to predict whether a customer will churn or not based on various features related to their service usage and personal information.

The main goal is to:
- Build machine learning models to **predict customer churn**.
- Compare the performance of different models using various evaluation metrics.
- Visualize insights and customer behavior patterns using **Power BI**.

##  Dataset

- Source: [Telco Customer Churn dataset on Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
- Description: The dataset contains information about customer demographics, account information, services signed up for, and whether they churned or not.

  ##  Tools & Technologies

- **Python** (Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib)
- **Jupyter Notebooks / Kaggle Notebooks**
- **Power BI** for dashboard creation and visual analysis
- **Git & GitHub** for version control and sharing the project

## Data Preprocessing

- Handled missing values
- Converted categorical variables to numerical using encoding techniques
- Normalized/standardized numerical features
- Removed irrelevant or duplicated columns

##  Machine Learning Models

Three machine learning models were trained and evaluated:

1. **XGBoost**
2. **Random Forest**
3. **LightGBM**

Each model was evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion matrix
- Classification report
- Cross Validation

##  Results & Insights

- Compared models to find the best fit for this problem.
- Identified key features influencing customer churn.
- Gained business insights through visual analysis.
