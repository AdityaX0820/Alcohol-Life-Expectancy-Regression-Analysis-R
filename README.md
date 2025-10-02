# Alcohol Consumption & Life Expectancy Regression Analysis (R)

This project explores the relationship between alcohol consumption and life expectancy across countries using regression analysis in R. It demonstrates both simple linear and non-linear regression models, provides a thorough correlation analysis, and visualizes the results with high-quality plots.

## Project Overview

- **Goal:** Investigate how alcohol consumption impacts life expectancy globally.
- **Dataset:** [Life Expectancy Data.csv](https://github.com/AdityaX0820/Alcohol-Life-Expectancy-Regression-Analysis-R/blob/main/Life%20Expectancy%20Data.csv)
- **Methodology:** 
  - Data cleaning and preprocessing
  - Exploratory data analysis (EDA)
  - Manual and in-built correlation calculation
  - Regression modeling (both simple linear and polynomial regression)
  - Model evaluation (RMSE, R², correlation)
  - High-quality visualizations

## Files

- `Life Expectancy Data.csv`  
  Contains country-wise data including alcohol consumption, life expectancy, mortality, and other health indicators.

- `Project_Code.R`  
  Main R script for the analysis. Includes data cleaning, correlation analysis, regression modeling, and visualization steps.

- `Final Project Report (1).pdf`  
  Detailed report with background, methodology, results, and interpretations.

## How to Run

1. **Install Dependencies:**  
   The following R packages are required:
   - `ggplot2`
   - `tidyverse`
   - `dplyr`
   - `GGally`
   - `caTools`
   - `MLmetrics`
   - `caret`
   - *(Optional)* `plotly` for interactive plots

   Uncomment and run the install lines in `Project_Code.R` if needed.

2. **Load the Data:**  
   When prompted, select `Life Expectancy Data.csv` as the input file.

3. **Run Analysis:**  
   Execute `Project_Code.R` in RStudio or your preferred R environment. The script will:
   - Clean and preprocess the data
   - Calculate correlations manually and with built-in functions
   - Perform regression analyses
   - Output evaluation metrics
   - Generate plots

## Key Analytical Steps

### 1. Data Cleaning

- Removes missing values ensuring robust analysis.
- Selects relevant features: `Life.expectancy` and `Alcohol`.

### 2. Correlation Analysis

- **Manual Calculation:**  
  Direct computation of the correlation coefficient between alcohol consumption and life expectancy.
- **Built-in Calculation:**  
  Uses `GGally::ggcorr` for correlation matrix visualization.

### 3. Regression Modeling

#### Simple Linear Regression

- Manual computation of regression coefficients (`b0`, `b1`).
- Visualizes the regression line and scatter plot.
- Evaluates model performance with R² and RMSE.

#### Polynomial Regression (Non-Linear)

- Fits a 4th-degree polynomial using `lm()` and `poly()`.
- Compares model performance to linear regression.
- Visualizes non-linear fit.

### 4. Model Evaluation

- **RMSE:** Root Mean Squared Error
- **R²:** Coefficient of determination
- **Manual and Built-in metrics:** Ensures result reliability

### 5. Visualization

- High-quality plots for both regression fits.
- Correlation heatmap for feature relationships.

## Results

- **Correlation:** Quantifies the relationship between alcohol consumption and life expectancy.
- **Regression Models:** Show how alcohol consumption can be used to predict life expectancy, with non-linear models often performing better.
- **Insights:** Helps inform public health policy and awareness about alcohol's impact on longevity.

## Sample Output

- **Correlation Coefficient**
- **Regression Equation & Visualization**
- **R² and RMSE for model comparison**

