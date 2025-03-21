# Housing-Price-Prediction-Model
# Enhanced Multivariate Regression Analysis

## Overview
This project presents an enhanced implementation of multivariate regression analysis applied to the California Housing dataset. The code extends and improves upon the original implementation from ["Mastering ML with Python in Six Steps"](https://github.com/Apress/mastering-ml-w-python-in-six-steps/blob/master/Chapter_3_Code/Code/Multivariate%20Regression.ipynb) by incorporating comprehensive data analysis techniques, advanced visualizations, and detailed model evaluation.

## Features

### 1. Data Preparation and Exploration
- Loading and exploration of the California Housing dataset
- Comprehensive statistical analysis of features
- Advanced visualizations including:
  - Feature distributions with KDE plots
  - Correlation heatmap with annotated correlation values
  - Pairwise relationships between key features
  - 3D visualization of relationships between features and target

### 2. Feature Engineering
- Standardization of features
- Creation of polynomial features
- Principal Component Analysis (PCA) for dimensionality reduction
- Visualization of data in principal component space

### 3. Model Training and Evaluation
- Implementation of multiple regression models:
  - Linear Regression
  - Ridge Regression
  - Lasso Regression
  - ElasticNet
- Comprehensive model evaluation using:
  - Root Mean Squared Error (RMSE)
  - R-squared (R²)
  - Mean Absolute Error (MAE)
  - Cross-validation scores
  - Training time comparison
- Visualization of model performance metrics

### 4. Hyperparameter Tuning
- Grid search for optimal hyperparameters on:
  - Ridge (alpha values)
  - Lasso (alpha values)
  - ElasticNet (alpha and l1_ratio values)
- Visualization of hyperparameter effects on model performance

### 5. Residual Analysis
- Detailed residual analysis for training and test sets
- Residuals vs. predicted values plots
- Histograms of residual distributions
- Q-Q plots for normality assessment
- Actual vs. predicted value comparison

### 6. Feature Importance Analysis
- Analysis of feature coefficients to determine importance
- Visualization of feature importance with color-coded bars

## Improvements Over Original Implementation
This implementation enhances the original code with:
- Modern visualization techniques with improved aesthetics
- More comprehensive model evaluation and comparison
- Advanced feature engineering techniques
- Detailed residual analysis
- Better code organization and documentation
- Higher quality visualizations saved for future reference

## Requirements
The code requires the following Python libraries:
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib

## How to Use
1. Clone this repository
2. Install the required dependencies
3. Run the Jupyter notebook to see the full analysis
4. Review the generated visualizations in the output directory

## Results
The analysis identifies the most significant factors affecting housing prices in California and provides a comparative evaluation of different regression techniques. Key findings include:
- The most important predictors of housing prices
- Comparative performance of different regression models
- Optimal hyperparameters for regularized regression models
- Validation of model assumptions through residual analysis

## License
This project is available under the MIT License.

## Acknowledgments
- Original code from "Mastering ML with Python in Six Steps" by Manohar Swamynathan
- California Housing dataset from the StatLib repository
