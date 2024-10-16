Sales Prediction Model:
Overview:
This project aims to develop a regression model that predicts future sales based on historical sales data. The objective is to help businesses with accurate forecasting, which can improve decision-making and resource allocation for inventory management, marketing, and budgeting.

Project Goals:
Predict Future Sales: Develop a model that can forecast sales accurately.
Improve Resource Allocation: Use the predictions for better inventory management, budgeting, and marketing strategies.
Performance Evaluation: Assess the model's accuracy using appropriate metrics.

Tasks Completed:
Data Gathering: Collected historical sales data for analysis.
Data Preprocessing:
Handled missing values.
Encoded categorical variables.

Model Training:
Trained various regression models, including linear regression and random forest.

Model Evaluation: Evaluated model performance using metrics such as R squared Score (R2) and Mean Squared Error (MSE).
Prediction: Used the trained model to make sales predictions.

Getting Started:
To get started with the code, follow these steps:
Prerequisites:
Python 3.x
Libraries: pandas, numpy, scikit-learn, matplotlib, seaborn, jupyter

Data Preprocessing:
Handling Missing Values: Imputed missing values using mean/mode as applicable.
Encoding Categorical Variables: Used one-hot encoding and ordinal encoding for categorical variables to convert them into numerical values and found that one-hot encoding gave better results.

Model Training and Evaluation:
Trained different regression models:
Linear Regression
Random Forest Regressor

Evaluation Metrics: Used MSE and R2 Score to evaluate the performance of the models.

Results:
The performance of the regression models was evaluated using Mean Squared Error (MSE) and R² Score for both ordinal and one-hot encoding techniques.

Model Performance (Ordinal Encoding):
Random Forest
MSE: 1,315,355.45
R² Score: 0.5506
Linear Regression
MSE: 1,426,176.83
R² Score: 0.5127
Model Performance (One-Hot Encoding):
Random Forest
MSE: 1,296,817.43
R² Score: 0.5569
Linear Regression
MSE: 1,283,097.67
R² Score: 0.5616

Summary:
The Linear Regression model with One-Hot Encoding achieved the best performance with the lowest MSE (1,283,097.67) and the highest R² score (0.5616), indicating that it better explained the variance in the data.
The Random Forest model with One-Hot Encoding also performed well, showing improvement over the models using ordinal encoding.

Conclusion:
This project demonstrated the application of regression models for sales prediction using historical data. The results showed that encoding techniques significantly impact model performance. In particular:

One-Hot Encoding proved to be more effective than Ordinal Encoding, resulting in better accuracy and lower error across both models.
The Linear Regression model with One-Hot Encoding achieved the best performance with the lowest MSE and highest R² Score, making it the most suitable choice for this dataset.
These findings highlight the importance of feature encoding in predictive modeling. By improving the accuracy of sales forecasts, the project helps support better inventory management, budgeting, and marketing decisions. Future work could explore more advanced techniques, such as hyperparameter tuning or additional feature engineering, to further enhance prediction accuracy.
