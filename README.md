# Parkinsons-Detection-PCA-XGBoost
## Context
Lane detection is an essential element of self-driving cars and autonomous vehicles. Using lane detection, the vehicle will know where to go and avoid the risk of running into other lanes or getting off the road. This can prevent the car from drifting off the driving lane. 

## Dataset
* Kaggle Dataset - [Parkinson's Data Set](https://www.kaggle.com/nidaguler/parkinsons-data-set)

## Objective
* Explore the Parkinson's Dataset variance and it's explainability through PCA
* Detect Parkinson's with XGBoost

## Steps
1. Load in Parkinson Dataset
2. Frame Mask Creation
3. Feature Engineering 
    * Image Thresholding
    * Hough line Transformation
4. Video Preparation

## Results
* PCA was used to successfuly preserve the datasets variance by reduce the number of columns to 2 or 3.
* We used an XGBClassifier for this and made use of the sklearn library to prepare the dataset. This gives us an accuracy of <b> 96.66%</b>


## References
* https://towardsdatascience.com/getting-started-with-xgboost-in-scikit-learn-f69f5f470a97
* https://towardsdatascience.com/principal-component-analysis-pca-explained-visually-with-zero-math-1cbf392b9e7d
