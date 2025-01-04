Project Overview
This project aims to predict car purchase amounts based on customer demographic and financial data using a Decision Tree Regression model. The dataset includes features such as Age, Annual Salary, Credit Card Debt, Net Worth, and Gender.

Dataset
Source: Car_Purchasing_Data.csv
Key Features:
Age,Annual Salary,Credit Card Debt,Net Worth,Gender,Car Purchase Amount,Preprocessing Steps

Data Cleaning:
Removed unwanted characters from 'Customer Name'.
Ensured 'Age' is of integer type.
Handling Missing Values:
Verified and ensured no null values are present.

Feature Scaling:
Applied StandardScaler to standardize numerical features.
Outlier Removal:
Used the IQR method to detect and remove outliers in numerical columns.
Exploratory Data Analysis (EDA)
Boxplots were created for:
Age,Annual Salary,Credit Card Debt,Net Worth,Model Training,

Algorithm: Decision Tree Regressor
Model Evaluation Metric: R² Score

Results
The accuracy of the model was evaluated using the R² score.

How to Run
Install required libraries:
pip install numpy pandas matplotlib scikit-learn

Place Car_Purchasing_Data.csv in the appropriate directory.
Run the Python script.
Visualization
Boxplots for numerical features
Decision Tree Visualization using plot_tree

