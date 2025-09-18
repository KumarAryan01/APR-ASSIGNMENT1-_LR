# APR-ASSIGNMENT1-_LR

Linear Regression Model Analysis
This notebook performs a linear regression analysis on a dataset to predict house prices.

Dataset
The analysis uses data from data.csv. The dataset contains information about various house features and their corresponding prices.

Analysis Steps
Data Loading and Exploration: The data was loaded into a pandas DataFrame. Initial exploration included viewing the first few rows, checking for missing values, and examining data types. No missing values were found.

Data Preprocessing: Irrelevant columns (date, street, city, statezip, country) were dropped. The target variable (price) was separated from the features.

Data Splitting: The data was split into training (80%) and testing (20%) sets to train and evaluate the model.

Model Building and Training: A linear regression model from scikit-learn was instantiated and trained on the training data.

Model Evaluation: The model's performance was evaluated using Mean Squared Error (MSE) and R-squared (R2) on the test set.

Mean Squared Error: 986,921,767,056.10
R-squared: 0.0323
Visualization: Scatter plots were generated to visualize the relationship between 'sqft_living' and 'price', and to compare actual versus predicted prices.

Findings and Conclusion
The linear regression model achieved a very low R-squared score (0.0323), indicating that it explains only a small portion of the variance in the house prices. The scatter plot of actual versus predicted prices also shows a poor fit, with predictions not closely aligned with the actual values.

The results suggest that a simple linear regression model is not sufficient to accurately predict house prices with this dataset and the selected features.

Next Steps
Explore other regression models (e.g., polynomial regression, decision trees, random forests) that might capture non-linear relationships.
Consider feature engineering to create new features or transform existing ones.
Investigate potential outliers or data inconsistencies that might be affecting the model's performance.
