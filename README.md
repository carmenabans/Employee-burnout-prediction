# Employee Burntout Prediction using Machine Learning

## Introduction:
This project aims to build models using various preprocessing techniques to predict employee burnout. The dataset used was collected by the HR department of a company that is concerned about its employee attrition (burnout) rate.

## Includes:
1. **Exploratory Data Analysis (EDA)**: Performed a simplified EDA to understand the dataset, including the number of instances and attributes, attribute types, constant or unnecessary columns, missing values, problem type (classification or regression), and whether the dataset is imbalanced.
2. **Data Split**: Divided the data into a training set for model training and hyperparameter tuning, and a test set for evaluation. Used stratified partitioning and appropriate metrics for imbalanced classification problems, such as balanced_accuracy, f1, and confusion matrix.
3. **Model Construction**: Implemented a LogisticRegression model as the baseline (without hyperparameter tuning) and a Boosting model as the advanced model (with hyperparameter tuning). Used pipelines for preprocessing and considered using external libraries like xgboost

   The seed for random number generation is fixed to ensure reproducibility.
5. **Attribute Selection**: Used a filter-based attribute selection method, such as SelectKBest with f_classif, mutual_info_classif, or chi2, to improve the results and extract conclusions about the most important attributes.

## Team
* Carmen Abans Maciel: https://github.com/carmenabans
* Noelia Hernández Rodríguez: https://github.com/Noeliahr10

## References:
* Pandas: https://pandas.pydata.org
* NumPy: https://numpy.org
* Scikit-learn: https://scikit-learn.org/stable/
* XGBoost: https://xgboost.readthedocs.io/en/stable/

