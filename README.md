# Insurance Cost Prediction

## About the Project

This project focuses on predicting medical insurance charges using
Machine Learning.

The dataset contains information about age, sex, BMI, children, smoking
status, and region. I performed data preprocessing and built regression
models to predict insurance charges.

## Column Details

- `age` - Age of the person
- `sex` - Male or Female
- `bmi` - Body Mass Index
- `children` - Number of children
- `smoker` - Smoking status
- `region` - Residential region
- `charges` - Medical insurance charges

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Data Preprocessing

The following preprocessing steps were performed:

- Loaded the dataset
- Filled missing values in `children` with `0`
- Filled missing `bmi` values with the mean
- Performed exploratory data analysis
- Created scatter and bar plots
- Encoded categorical columns into numerical values
- Applied feature scaling

## Machine Learning Models

### Linear Regression

Built a Linear Regression model to predict insurance charges.

Evaluated the model using:

- Training Score
- Test Score
- Slope
- Intercept
- Mean Squared Error (MSE)
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

### Random Forest Regression

Also built a Random Forest Regression model and evaluated its performance
using:

- Training Score
- Test Score
- Mean Squared Error (MSE)
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

## Data Visualization

The project includes:

- Scatter plot between Age and Children
- Bar plot between BMI and Children

## What I Learned

- Data cleaning and preprocessing
- Handling missing values
- Encoding categorical data
- Feature scaling
- Data visualization
- Building regression models
- Evaluating Machine Learning models
- Comparing Linear Regression and Random Forest Regression

## Author

**Jinesh Suthar**

Aspiring Data Analyst
