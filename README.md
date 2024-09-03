# Multiple-Linear-Regression
### Toyota Corolla Price Prediction using Multiple Linear Regression
### Project Overview
This project involves performing a multiple linear regression analysis to predict the price of Toyota Corolla cars based on various attributes, such as age, accumulated kilometers, fuel type, horsepower, and more. The project includes data preprocessing, model building, evaluation, and the application of Lasso and Ridge regression techniques.

### Dataset Description
The dataset consists of the following variables:

1. Age: Age in years
2. KM: Accumulated Kilometers on the odometer
3. FuelType: Fuel Type (Petrol, Diesel, CNG)
4. HP: Horse Power
5. Automatic: Automatic (Yes=1, No=0)
6. CC: Cylinder Volume in cubic centimeters
7. Doors: Number of doors
8. Weight: Weight in Kilograms
9. Quarterly_Tax: Quarterly tax in EUROs
10. Price: Offer Price in EUROs
### 1. Exploratory Data Analysis (EDA)
1. Objective: Gain insights into the dataset and understand the relationships between variables.
2. Visualizations:
Histograms of numerical variables.
Boxplots to detect outliers.
Pair plots to examine relationships between variables.
Correlation matrix to identify multicollinearity.
3. Summary Statistics: Mean, median, standard deviation, and range of all variables.
### Data Preprocessing:
1. Handling missing values.
2. Encoding categorical variables (FuelType, Automatic).
3. Standardizing/normalizing features.
### 2. Data Splitting
1. Objective: Split the dataset into training and testing sets.
2. Method:
80% of the data for training.
20% of the data for testing.
### 3. Model Building
1. Objective: Build multiple linear regression models to predict the price.
### Models Developed:
1. Model 1: Basic model including all features.
2. Model 2: Model with feature selection based on p-values and correlation analysis.
3. Model 3: Model with interaction terms or polynomial features.
4. Interpretation: Coefficients of the models were analyzed to understand the impact of each feature on the price.
### 4. Model Evaluation
1. Objective: Evaluate the performance of the models using testing data.
2. Evaluation Metrics:
3. R-squared: Proportion of variance explained by the model.
4. Mean Absolute Error (MAE): Average absolute difference between predicted and actual values.
5. Root Mean Squared Error (RMSE): Square root of the average squared differences between predicted and actual values.
### 5. Lasso and Ridge Regression
1. Objective: Apply regularization techniques to improve the model's generalization.
2. Methods Applied:
a. Lasso Regression: Penalizes the absolute size of coefficients, useful for feature selection.
b. Ridge Regression: Penalizes the square of coefficients, helps in handling multicollinearity.
3. Comparison: The performance of Lasso and Ridge models compared with the original models using the same evaluation metrics.
### Conclusion
The project successfully predicted the price of Toyota Corolla cars using multiple linear regression models. The application of Lasso and Ridge regression further refined the models, demonstrating the effectiveness of regularization techniques in improving model performance and interpretability.



