# Rainfall-Prediction

**Project Type**: Machine Learning | Classification  
**Tools Used**: Python, Pandas, Matplotlib, Scikit-Learn, XGBoost, GridSearchCV, RandomizedSearchCV  
**Dataset**: Rainfall Prediction Dataset [Kaggle](https://www.kaggle.com/competitions/playground-series-s5e3/data)

### **Objective**

The objective of this project was to predict whether or not it would rain based on various weather features such as temperature, humidity, wind speed, and cloud cover. The goal was to explore the relationships between these features and rainfall, and to build a predictive model to forecast rainfall outcomes.

### **Key Steps**

- **Exploratory Data Analysis (EDA)**:
  - Analyzed the dataset to understand the relationships between features and rainfall.
  - Visualized the distribution of features such as temperature, humidity, and cloud cover, and their correlation with the target variable.
  - Handled missing data, including imputation and removal of unnecessary columns.
- **Data Preprocessing & Feature Engineering**:
  - Scaled continuous features and encoded categorical variables.
  - Created new features like "feels like" temperature by combining temperature and humidity.
  - Encountered complications with feature engineering, which led to technical debt, requiring code refactoring before further modifications.
- **Model Training & Evaluation**:
  - Trained multiple models, including **Logistic Regression**, **XGBoost**, **Random Forest**, and **SVC**.
  - Used **RandomizedSearchCV** and **GridSearchCV** for hyperparameter tuning to improve model performance.
  - Compared model results, with Logistic Regression emerging as the best-performing model in terms of efficiency and accuracy.

### **Results**

The best-performing model was **Logistic Regression**, with an accuracy of **89.68%** (ROC-AUC score). Key features such as **temperature**, **humidity**, and **wind speed** were found to have strong relationships with rainfall prediction, but further feature engineering could improve results.

🔗 **View Interactive Notebook (nbviewer)**: [nbviewer Link](https://nbviewer.org/github/christopherFlynn/Rainfall-Prediction/blob/main/rainfall-prediction.ipynb)
