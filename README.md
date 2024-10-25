# House Price Predictor

This project applies machine learning techniques, including **linear regression**, **feature engineering**, and **data normalization**, to predict house prices based on various property attributes.

## Overview

The House Price Predictor is designed to analyze housing market data, focusing on key property features such as location, square footage, number of bedrooms, and more. Using a linear regression model, the project aims to provide accurate price predictions based on these attributes, demonstrating effective data preprocessing, feature selection, and model evaluation techniques.

## Technologies

- **Python**: Core programming language
- **Pandas**: Data manipulation and cleaning
- **Scikit-Learn**: Machine learning library for regression and evaluation
- **Matplotlib / Seaborn**: Data visualization

## Project Structure

- `data/`: Contains housing market datasets
- `notebooks/`: Jupyter notebooks for exploratory data analysis and model training
- `src/`: Scripts for data preprocessing, feature engineering, and model training
- `results/`: Model evaluation metrics and visualizations

## Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/tranhoangminh1412/house-price-predictor
   cd house-price-predictor
2. Usage
- Data Preprocessing: Run preprocess.py in src/ to clean and preprocess the dataset.
- Model Training: Execute train_model.py to train and evaluate the linear regression model.
- Prediction: Use predict.py to make price predictions for new property data.
3. Results
- The linear regression model performs well on the test data, accurately predicting house prices based on key property attributes. Visualization tools in this project illustrate the relationships between features and predicted prices.

## Future Work
   - Experiment with additional models (e.g., Random Forest, Gradient Boosting)
   - Integrate more features, such as neighborhood crime rates and school ratings
## License
This project is licensed under the MIT License.

