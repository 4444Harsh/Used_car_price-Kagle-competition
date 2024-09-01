# Used_car_price-Kagle-competition
# Car Price Prediction Competition

This repository contains my solution for the Kaggle competition on predicting car prices. The goal of the competition is to build a model that can accurately predict the prices of cars based on various features such as brand, model, fuel type, engine, and more.

## Files in this Repository

- **`train.csv`**: The training dataset used to build the model.
- **`test.csv`**: The test dataset on which predictions were made.
- **`submission.csv`**: The submission file containing my final predictions that scored 85899.60981.
- **`notebook.ipynb` or `script.py`**: The code used to preprocess the data, train the model, and generate predictions.
- **`README.md`**: This file, providing an overview of the project and approach.

## Approach

1. **Data Preprocessing**:
   - Categorical columns were imputed with the most frequent value.
   - Numerical columns were imputed with the median value.
   - A custom label encoder was used to handle unseen labels in categorical data.

2. **Modeling**:
   - A `RandomForestRegressor` model was trained on the preprocessed data.
   - The model was validated using a mean absolute error (MAE) metric.

3. **Results**:
   - The final model achieved a MAE of [Your MAE here] on the validation set.
   - The final submission scored 85899.60981 on the test set.

## How to Use

1. Clone this repository.
2. Run the provided notebook or script to reproduce the results.
3. Use the provided `submission.csv` to view the predictions made by the model.

## Requirements

- Python 3.x
- pandas
- scikit-learn

## Acknowledgments

Thanks to Kaggle for providing the platform and dataset for this competition.
