# Income-Data---Regression-ML-model
Income prediction using Regression Machine Learning models
# Income and Happiness Prediction – Regression ML

## Project Overview

This project analyzes the relationship between **Income and Happiness** using statistical analysis and Machine Learning.

A **Linear Regression** model is developed to predict happiness based on income. The project also uses **Ordinary Least Squares (OLS)** statistical modeling to understand the relationship between the independent and dependent variables.

The analysis demonstrates how regression can be used to understand and predict a continuous target variable.

## Dataset

The dataset contains **498 records** with the following columns:

| Column | Description |
| income | Income value |
| happiness | Happiness score |
| Unnamed: 0 | Record/index column |

### Dataset Information

- Number of Records: 498
- Number of Columns: 3
- Target Variable: `happiness`
- Independent Variable: `income`
- Missing Values: None

## Exploratory Data Analysis

The following analysis was performed:

- Dataset inspection
- Data types identification
- Statistical summary
- Dataset shape and size analysis
- Missing value checking
- Histogram visualization
- Scatter plot analysis

### Relationship Analysis

A scatter plot was created to visualize the relationship between **income and happiness**.

The analysis shows a positive relationship between income and happiness in the dataset.

## Data Preprocessing

The dataset was checked for:

- Missing values
- Data types
- Statistical properties
- Feature and target variables

The independent variable was defined as:

`income`

The dependent variable was defined as:

`happiness`

## Train-Test Split

The dataset was divided into training and testing sets.

- Training Data: 80%
- Testing Data: 20%
- Random State: 1

The training data was used to build the regression model, while the testing data was used to evaluate its performance.

## Statistical Modeling – OLS

An **Ordinary Least Squares (OLS)** regression model was built using `statsmodels`.

The model summary produced:

- R-squared: 0.749
- Adjusted R-squared: 0.749
- F-statistic: 1483
- Prob (F-statistic): 3.96e-151

The estimated regression relationship was:

**Happiness = 0.2043 + 0.7138 × Income**

The income coefficient indicates a positive relationship between income and the predicted happiness score within this dataset.

## Machine Learning Model

### Linear Regression

A Linear Regression approach was used to model the relationship between income and happiness.

The model learns the relationship between:

**Input:** Income

**Output:** Happiness

## Model Evaluation

The model was evaluated using the following metrics:

| Metric | Value |
| RMSE | 0.7426 |
| R² Score | 0.7401 |
| Adjusted R² | 0.7348 |

### RMSE

Root Mean Squared Error (RMSE) measures the average magnitude of prediction errors.

Lower RMSE generally indicates smaller prediction errors.

### R² Score

R² measures how much of the variation in the target variable is explained by the model.

The model achieved an R² score of approximately **0.74** on the test data.

### Adjusted R²

Adjusted R² accounts for the number of predictors used in the regression model.

The test-set Adjusted R² obtained in the notebook was approximately **0.735**.

## Visualizations

The project includes:

- Histogram visualization
- Income vs Happiness scatter plot
- Statistical regression analysis
- Model performance evaluation

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Statsmodels
- Scikit-learn
- Jupyter Notebook

## Key Features

- Exploratory Data Analysis
- Missing value analysis
- Statistical data analysis
- Income and happiness relationship analysis
- OLS regression
- Linear Regression
- Train-test split
- RMSE calculation
- R² calculation
- Adjusted R² calculation
- Data visualization

## Skills Demonstrated

- Python Programming
- Data Analysis
- Exploratory Data Analysis (EDA)
- Statistical Analysis
- Regression Analysis
- Linear Regression
- OLS Regression
- Model Evaluation
- Data Visualization
- Pandas
- NumPy
- Scikit-learn
- Statsmodels

## Project File

- `Income Data - Regression ML model.ipynb` – Complete Jupyter Notebook containing data analysis, visualization, OLS regression, Linear Regression, and model evaluation.

## Conclusion

This project demonstrates how **Linear Regression and statistical regression techniques** can be used to analyze the relationship between income and happiness.

The model achieved an R² score of approximately **0.74** on the test data, demonstrating that income explains a substantial portion of the variation in happiness within this dataset.
