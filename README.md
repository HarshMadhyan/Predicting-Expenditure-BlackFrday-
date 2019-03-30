# Expenditure Prediction
This is my solution for AnalyticsVidya Hackathon,given attributes like gender, age, years at occupation, city, etc. I use classical, ensemble, basic neural and blended ensemble methods for accurate prediction. 
I achieve RMSE of approx. 2889. (Kaggle Top 60)

This dataset contains information about buyer (Age, Gender, Occupation,etc) as well as the number of products bought from 3 different categories and the total purchase amount.
Our task here is to predict the purchase amount (Regression Analysis) given the said features.

# Procedure Followed
First I performed preliminary data exploration and visualization for ages and years of occupation, city-category. Then I did some feature engineering as follows:
1) Binarize Gender
2) Label Encode Age Categories 
3) One Hot Encode City Category
4) Perform Imputation (strategy = Median) for missing values in Product Category

Then I used train-test-split and tried few penalized regression models as well as tree based models and ensemble learning.
I finally got RMSE of 2889 using Blend Ensemble of XGBoost and Adaboost. 
