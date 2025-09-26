# Customer Churn Prediction Project  

This repository contains an end-to-end machine learning workflow to analyze client and price data, perform exploratory data analysis (EDA), feature engineering, and build predictive models.  

---

## Project Goal  
The goal of this project is to analyze client and price data to predict customer behavior.  

Key steps include:  
- Exploratory Data Analysis (EDA)  
- Feature Engineering  
- Machine Learning Model Training & Evaluation  

---

## Data Description  

| Dataset | Description | Key Columns |
|---------|-------------|-------------|
| **client_data.csv** | Client-specific information | client_id, activity_new, cons_12m, cons_gas_12m, margin_net_pow_elec, pow_max |
| **price_data.csv**  | Historical price information | client_id, price_date, price_p1_var, price_p2_fix |
| **data_for_predictions.csv** | Prepared dataset for ML predictions (post feature engineering) | Derived from client & price data |

---

## Notebooks  

### Task 2 - eda_starter.ipynb  
- Load & inspect data (types, missing values)  
- Summary statistics  
- Visualizations (distributions, correlations)  
- Identify data quality issues  

### Task 3 - feature_engineering.ipynb  
- Create new features (time-based, interactions)  
- Handle categorical & numerical transformations  
- Treat outliers / missing data  
- Prepare final dataset for modeling  

### Task 4 - modeling_starter.ipynb  
- Train-test split  
- Select & train ML models  
- Predict on test data  
- Evaluate using metrics (accuracy, precision, recall, f1)  
- Hyperparameter tuning (if required)  

---

## Project Structure  
The project is organized with the following key files and directories:

-   **/content/**: The root directory containing all project files.
    -   `client_data.csv`: Contains client-specific information, including account details and historical consumption data. Used as a primary source for analysis and feature engineering.
    -   `price_data.csv`: Contains historical price information. Used to analyze pricing trends and potentially create price-related features.
    -   `data_for_predictions.csv`: This dataset is likely the output of the feature engineering process, containing features prepared for training the machine learning model.
    -   `Data Description (1).pdf`: Provides detailed descriptions of the columns in the client and price datasets, crucial for understanding the data.
    -   `Task 2 - eda_starter.ipynb`: Jupyter notebook for Exploratory Data Analysis (EDA). This notebook is used to understand the data, visualize distributions, identify patterns, and check for data quality issues.
    -   `Task 3 - feature_engineering.ipynb`: Jupyter notebook for Feature Engineering. This notebook is where new features are created, data transformations are applied, and the final dataset for modeling is prepared.
    -   `Task 4 - modeling_starter.ipynb`: Jupyter notebook for Model Training and Evaluation. This notebook is used to build, train, evaluate, and potentially tune machine learning models for predictions.
"""
