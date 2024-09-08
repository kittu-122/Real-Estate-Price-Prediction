# Real Estate Price Prediction

## Overview

This project focuses on building a machine learning model to predict real estate prices based on various features such as size, number of bedrooms (BHK), total square footage, and location. The dataset used is specific to real estate data from Bengaluru, India.

## Dataset

The dataset used in this project is **Bengaluru House Data**, which includes the following features:
- `area_type`: Type of area (e.g., Super Built-up Area, Plot Area, Carpet Area)
- `availability`: Whether the property is ready to move in
- `location`: Location of the property in Bengaluru
- `size`: Number of bedrooms (BHK)
- `society`: The society in which the property is located
- `total_sqft`: Total square footage of the property
- `bath`: Number of bathrooms
- `balcony`: Number of balconies
- `price`: Price of the property in lakhs

## Steps Involved

### 1. Data Cleaning
- Handling missing values by dropping rows with null values.
- Converting non-numeric data to a usable format (e.g., converting ranges in the `total_sqft` column to average values).
- Removing outliers based on BHK values and total square footage.

### 2. Feature Engineering
- Creating new features like `price_per_sqft` for more detailed analysis.
- Grouping and simplifying location data to reduce dimensionality.

### 3. Model Building
The machine learning models are built and trained using common algorithms such as:
- Linear Regression

### 4. Model Evaluation
The models are evaluated using performance metrics such as:
- Mean Absolute Error (MAE)
- Root Mean Square Error (RMSE)

## Usage

To run this project, follow these steps:
1. Clone the repository and navigate to the project directory.
2. Run the Jupyter notebook to view the entire workflow or execute each cell step by step to replicate the analysis.

## Major Libraries Used:
- `numpy`
- `pandas`
- `matplotlib`
- `scikit-learn`

## Conclusion
The project successfully predicts real estate prices in Bengaluru by training machine learning models and validating their performance. Further tuning of the models and data preprocessing can improve prediction accuracy.

## Contributing
Contributions to the project are welcome! Feel free to submit pull requests, report issues, or suggest enhancements to improve **Real Estate Price Prediction**.

**Thank you for choosing this project. We hope it proves useful and delivers a seamless experience for your needs!**
