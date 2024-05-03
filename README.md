# Car Resale Price Prediction

Reselling cars is a crucial task in the finance sector, often requiring accurate pricing predictions based on various criteria such as brand, model, year, engine, transmission type, fuel, accident history, and title status. This project automates the prediction process using machine learning models.

## Dataset

The project utilizes the `used_cars.csv` dataset available on Kaggle, containing relevant information for resale price prediction.

## Methodology

1. **Data Preprocessing**: Handled missing values and smoothed noisy data using Inter Quartile Range Method.
2. **Feature Encoding**: Converted categorical features into numeric ones using target encoding and one-hot encoding.
3. **Feature Scaling**: Scaled features using min-max normalization.
4. **Model Evaluation**: Analyzed the performance of five regression models: Linear Regression, Decision Tree Regressor, Random Forest Regressor, KNeighbor Regressor, and Support Vector Regressor.
5. **Model Selection**: Identified KNeighbor and Random Forest Regressor as top-performing models.
6. **Hyperparameter Tuning**: Planned for optimizing the selected models for improved performance.

## Performance Metrics

- Train score
- Test score
- Mean squared error
- Mean absolute error
- R2 score
- Root mean squared error

## Future Steps

1. Perform hyperparameter tuning on the KNeighbor and Random Forest Regressor models for optimization.
2. Deploy the most optimized model for the task of predicting resale prices for cars.

## Acknowledgement
Special thanks to Kaggle for providing the dataset used in this project.

