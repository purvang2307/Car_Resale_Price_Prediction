Car_Resale_Price_Prediction
Resaling car is one of the crucial task done in finance sector. 
Determining resaling price of the car using various criteria such as Brand, Model, Model_year, Engine, Transmission_Type, Fuel, Whether a car has met accident or not , clean_title and so on. This task can be automated using the predictive machine learning model. 
For this purpose firstly, I have used used_cars.csv data set which is available on kaggle and also I have uploaded here.
Then I have done first data preprocessing task such as handling missing values, smooth noisy data using Inter Quartile Range Method.
Feature Encoding is the proces of converting categorical features into numeric one. For this purpose I have used target encoding and one-hot encoding.
Feature Scaling, also known as Normalization is the process of scaling the featured into a small specified range. Here I have used minmax normalization.
Then I have analyzed performance of five regression model: Linear Regression, Decision Tree Regressor, Random Forest Regressor, KNeighbor Regressor and Support Vector Regressor.
I have used train_score, test_score, mean_squared_error, mean_absolute_error, r2_score and root_mean_squared_error to analyze the performance of this predictive models.
Out of this five predictive models, Kneighbor and Random Forest Regressor have performed well. So we can perform hyper parameter tuning on this two model and optimize them. Then the model which is more optimized can be deployed for the task of prediction of resale price for car.
