# House Prices Prediction

This project predicts the sale price of residential houses using machine learning techniques, based on the Kaggle House Prices: Advanced Regression Techniques dataset.

## Project Objective
Predict the sale price of houses using various features (size, location, age, number of rooms, etc.) to assist buyers, sellers, realtors, and researchers in making data-driven decisions.

## Dataset
- Source: [Kaggle - House Prices: Advanced Regression Techniques](https://www.kaggle.com/c/house-prices-advanced-regression-techniques)
- Files: `train.csv`, `test.csv`, `sample_submission.csv`

## Main Steps
1. **Data Loading & Exploration**: Load and inspect the dataset, check for missing values, and understand feature meanings.
2. **Data Cleaning**: Handle missing values, remove or impute as needed.
3. **Feature Engineering**: Create new features to improve model performance.
4. **Encoding**: Convert categorical variables to numeric using one-hot encoding.
5. **Model Training**: Train and evaluate models (Linear Regression, Random Forest, XGBoost).
6. **Hyperparameter Tuning**: Optimize model parameters for best performance.
7. **Feature Importance**: Analyze which features most influence house prices.

## How to Run
1. Clone this repository:
   ```sh
   git clone https://github.com/your-username/house_prices.git
   cd house_prices
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Add your `kaggle.json` API key to the project root.
4. Run the Jupyter notebook:
   ```sh
   jupyter notebook house_prices.ipynb
   ```

## File Descriptions
- `house_prices.ipynb`: Main notebook with all analysis and modeling steps.
- `train.csv`: Training data with features and target variable (`SalePrice`).
- `test.csv`: Test data for predictions.
- `columnMeanings.md`: Description of dataset columns (in Portuguese).
- `requirements.txt`: Python dependencies.

## Results
- The project compares different regression models and highlights the importance of feature engineering and hyperparameter tuning.
- Feature importance analysis provides insights into what most affects house prices.

## License
This project is for educational purposes. See [Kaggle's competition rules](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/rules) for dataset usage.
