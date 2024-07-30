**Name**: Revathi.N   
**Company**: CODTECH IT SOLUTIONS      
**ID** : CT4DA3934   
**Domain** : Data Analytics   
**Duration** : 5th July to 5th August (2024)

# Task2

# Predictive Modeling With Linear Regression Analysis

This project implements a simple linear regression model to analyze a dataset with continuous variables. It includes data preprocessing, model training, evaluation, and visualization.

## Features

- Data loading and preprocessing
- Handling of missing values
- Linear regression model implementation
- Model evaluation using Mean Squared Error (MSE) and R-squared
- Visualization of regression results and model diagnostics

## Dependencies

- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

## Usage

1. Ensure all dependencies are installed.
2. Place your dataset in CSV format at the path : 'dataset.csv' The main dataset containing restaurant information.
3. Update the 'feature_column' and 'target_column' variables with the appropriate column names from your dataset.
4. Run the script to perform the analysis.

## Script Workflow

1. Load the dataset and display initial information
2. Handle missing values
3. Split data into training and testing sets
4. Train a linear regression model
5. Make predictions and evaluate model performance
6. Generate visualizations:
   - Regression line plot
   - Residual plot
   - Actual vs. Predicted values plot

## Customization

You can adapt this script to your specific dataset by modifying:
- File path for the dataset
- Feature and target column names
- Test set size in the train-test split

## Output

The script outputs:
- Model performance metrics (MSE and R-squared)
- Three visualizations to assess model fit and accuracy

## Visualizations

1. **Linear Regression Model Plot**: Shows the scatter plot of actual values and the regression line.
2. **Residual Plot**: Displays the residuals to check for patterns or heteroscedasticity.
3. **Actual vs. Predicted Plot**: Compares the actual values with the model's predictions.
  
## Conclusion

This project demonstrates a simple yet effective approach to linear regression analysis, from data preprocessing to model evaluation and visualization. It provides a solid foundation for understanding and implementing basic predictive modeling techniques in Python.
