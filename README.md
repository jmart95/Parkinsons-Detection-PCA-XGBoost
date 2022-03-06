# Parkinsons-Detection-PCA-XGBoost
## Context
Through the used of computer science and medicine, recent discoveries unveil new algorithms to improve health information reporting on clinical decisions. For example, detecting Parkinson’s Disease through machine learning can bring insight to such decisions. 

## Dataset
* Kaggle Dataset - [Parkinson's Data Set](https://www.kaggle.com/nidaguler/parkinsons-data-set)

## Objective
* Explore the Parkinson's Dataset variance and it's explainability through PCA
* Detect Parkinson's with XGBoost

## Steps
1. Load in Parkinson Dataset
2. Perform EDA with PCA
3. Use MinMaxScaler for reduce label class for -1 to 1
4. Fit and evaluate with XGBoost

## Results
* PCA was used to successfuly preserve the datasets variance by reduce the number of columns to 2 or 3.
* We used an XGBClassifier for this and made use of the sklearn library to prepare the dataset. This gives us an accuracy of <b> 96.66%</b>


## References
* https://towardsdatascience.com/getting-started-with-xgboost-in-scikit-learn-f69f5f470a97
* https://towardsdatascience.com/principal-component-analysis-pca-explained-visually-with-zero-math-1cbf392b9e7d
* https://www.analyticsvidhya.com/blog/2021/05/data-science-in-healthcare/