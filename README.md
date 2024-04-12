# House Pricing Prediction

This repository contains code and resources for predicting house prices using machine learning with a focus on the XGBoost algorithm. The project aims to develop a robust model capable of accurately estimating house prices based on various features. The implementation includes data preprocessing, model training, evaluation, and prediction.

## Table of Contents

1. Introduction
2. Installation
3. Usage
4. Notebooks
    - Data Processing
    - Model Training
    - Model Evaluation
5. Evaluation Metrics
6. Contribution
7. License

## Introduction

The goal of this project is to develop a machine learning model capable of accurately predicting house prices based on various features. The XGBoost (eXtreme Gradient Boosting) algorithm is used for its effectiveness in handling structured data and providing high prediction accuracy.

## Installation

Clone the repository:

```bash
git clone <repository_url>
cd House_Pricing_Prediction
```

Install the required dependencies:

```bash
pip install -r requirements.txt
```

## Usage

To use this project, ensure you have the necessary modules installed:

- numpy
- pandas
- matplotlib
- seaborn
- scikit-learn
- xgboost

These modules can be installed via pip:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn xgboost
```

## Notebooks

Execute the notebooks one by one in order. The project is divided into three notebooks, each focusing on a specific aspect of the house pricing prediction process:

1. **Data Processing**: This notebook covers the preprocessing steps such as data cleaning, handling missing values, feature engineering, and data transformation.
2. **Model Training**: The model training notebook implements the XGBoost algorithm to train the machine learning model using the processed data.
3. **Model Evaluation**: This notebook evaluates the trained model's performance using evaluation metrics such as R squared error (R2 Score) and Mean Absolute Error (MAE).

## Evaluation Metrics

Two evaluation metrics are used to assess the performance of the model:

- **R squared error (R2 Score)**: Measures the proportion of the variance in the dependent variable that is predictable from the independent variables.
- **Mean Absolute Error (MAE)**: Represents the average of the absolute differences between the predicted and actual house prices.

## Contribution

Contributions are welcome! If you find any issues or have suggestions for improvement, please feel free to open an issue or submit a pull request. For major changes, please open an issue first to discuss the proposed changes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
