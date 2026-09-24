# Fuel Price and Consumption: Linear Regression

This project uses simple linear regression to study the relationship between fuel price and fuel consumption for petrol and diesel.

## Objective

The goal is to understand whether fuel price can help predict fuel consumption using a basic supervised learning model.

## Syllabus Level

This project covers the basic supervised learning syllabus:

- Introduction to machine learning
- Supervised learning
- Regression
- Simple linear regression
- Basic data visualization
- Basic model evaluation

No advanced machine learning algorithms are used.

## Dataset

The dataset is located at `dataset/fuel_data.csv`.

Columns:

- `Fuel_Type` - Petrol or Diesel
- `Fuel_Price_per_Litre` - fuel price per litre
- `Distance_km` - distance travelled
- `Fuel_Consumption_L_per_100km` - fuel consumed per 100 km

## Model

The notebook uses simple linear regression:

`Y = b0 + b1X`

Where:

- `X` = fuel price
- `Y` = fuel consumption

## Evaluation

The notebook demonstrates:

- MAE
- MSE
- RMSE
- R2 score

## Generated Charts

Generated charts are available in `outputs/charts/`.

## How to Run

1. Open `notebook/linear_regression_fuel.ipynb` in Jupyter Notebook.
2. Install Python, pandas, numpy, matplotlib, and scikit-learn.
3. Run the notebook cells from top to bottom.

## Project Structure

```text
TEAM_01_FUEL_LINEAR_REGRESSION/
├── README.md
├── dataset/
│   └── fuel_data.csv
├── notebook/
│   └── linear_regression_fuel.ipynb
└── outputs/
    ├── charts/
    │   ├── fuel_price_vs_consumption.png
    │   ├── average_fuel_price.png
    │   ├── linear_regression.png
    │   └── actual_vs_predicted.png
    └── model_results/
        └── model_results.csv
```