Name: SAM KEVIN ADEL
Company: CODTECH IT SOLUTIONS
ID:CT6WDS1682
Domain:Data Analytics
Duration:August 12th 2024 to September 27th 2024
Mentor:Sonthosh
Project :PREDICTIVE MODELING WITH LINEAR REGRESSION

Objective:
The goal of this project is to implement and evaluate polynomial regression models using a dataset with continuous target variables. The project involves data loading, preprocessing, model training, evaluation, and visualization. Advanced features such as hyperparameter tuning with Grid Search, feature scaling, and interactive plotting are also included to enhance the model's performance and usability.

Key Components:

Data Upload and Inspection:
Users upload a CSV file containing their dataset. The code reads the dataset into a Pandas DataFrame and displays the column names to help users identify the relevant feature and target columns.

Feature and Target Selection:
Users are prompted to specify the names of the feature (independent variable) and target (dependent variable) columns. The code checks for the validity of these columns to ensure they exist in the dataset.

Feature Scaling:
The feature data is standardized using StandardScaler to have a mean of 0 and a standard deviation of 1. This step is crucial for ensuring that polynomial feature transformations and subsequent model training are effective and consistent.

Polynomial Feature Transformation and Pipeline Setup:
A pipeline is created to streamline the polynomial feature transformation and model training processes. The PolynomialFeatures transformer and LinearRegression model are integrated into this pipeline.

Hyperparameter Tuning with Grid Search:
The project uses GridSearchCV to perform an exhaustive search over a specified range of polynomial degrees. This technique identifies the polynomial degree that yields the best performance according to the R-squared metric.

Model Training and Evaluation:
The dataset is split into training and testing sets. The model is trained on the training set, and its performance is evaluated on the test set. Metrics such as Mean Squared Error (MSE), R-squared (R²), and Mean Absolute Error (MAE) are calculated to assess the model's accuracy and predictive power.

Visualization:
The project uses Plotly for interactive visualization. A scatter plot is created to show actual vs. predicted values, and a regression line is overlaid to illustrate the model's fit. This visualization helps in understanding how well the model performs and where improvements might be needed.

Model Saving and Loading:
The trained model can be saved to a file for future use or reloaded from a previously saved file. This feature ensures that the model can be reused without retraining, saving time and computational resources.

Advanced Features:
Interactive Visualization: Plotly is used for interactive plots, providing a more engaging and detailed view of the results compared to static plots.
Model Selection and Optimization: Grid search for hyperparameter tuning ensures that the best polynomial degree is selected, optimizing the model's performance.
Comprehensive Evaluation: Multiple performance metrics (MSE, R², MAE) are used to provide a thorough assessment of the model's accuracy.
![regression](https://github.com/user-attachments/assets/a07ee68f-b532-4019-b782-8de1b609b211)
