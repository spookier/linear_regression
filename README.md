# linear_regression

A simple machine learning project to predict car prices based on mileage using **Linear Regression** and **Gradient Descent**

## How to Use

1. **Install dependencies**: `pip install -r requirements.txt`
2. **Train the model**: Run `trainer.ipynb`
4.  This will read `data.csv`, normalize the data, and save the weights to `theta_settings.txt`
5. **Make a prediction**: Run `predictor.ipynb` then enter a mileage when prompted to see the estimated price

## Implementation Details
- **Algorithm**: Linear Regression with a single feature
- **Optimization**: Gradient Descent
- **Scaling**: Min-Max Normalization 
