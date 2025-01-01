# Stock Price Analysis: Toyota Motors

This project analyzes the historical stock prices of Toyota Motors (1980-2024) to identify trends, peaks, and troughs over the years. Using machine learning models, we predicted stock prices and evaluated their performance. Among the models trained, the Decision Tree Regressor demonstrated the best performance due to its ability to model non-linear patterns effectively.

## Project Overview

This repository contains:
- A Jupyter Notebook for analyzing Toyota's stock prices
- Data preprocessing and exploratory data analysis (EDA)
- Machine learning models trained to predict stock prices
- Model evaluation metrics and visualizations

Each Jupyter notebook contains model evaluation at the end to determine which model is the most accurate.

## Dataset

The dataset used for this project is sourced from Kaggle:
[Toyota Motors Stock Data (1980-2024)](https://www.kaggle.com/datasets/mhassansaboor/toyota-motors-stock-data-2980-2024).

### Features:
- Date
- Opening Price
- Closing Price
- High and Low Prices
- Volume

### Target:
- Predicting the Closing Price


## Models Trained

We trained and evaluated the following models:
1. ** Multiple Linear Regression**
2. Polynomial Regression
3. **Support Vector Regressor (SVR)**
4. **Random Forest Regressor**
5. **Decision Tree Regressor**

Among these, the Decision Tree Regressor yielded the best results with the highest R² score.


## Workflow

### 1. Data Preprocessing
- Handled missing values (if any).
- Scaled features for models that require normalization.

### 2. Exploratory Data Analysis (EDA)
- Visualized trends in stock prices over time.

### 3. Model Training and Evaluation
- Split the dataset into training and testing sets.
- Trained the models listed above.
- Evaluated model performance using:
  - R² Score

## Results

### Best Performing Model: Decision Tree Regressor
- **R² Score**: 0.99999
- Other metrics can be added as computed in the notebook.

### Insights:
- Toyota's stock prices exhibit clear trends over certain periods, driven by market and economic conditions.
- Decision Tree Regressor captures non-linear patterns effectively, making it suitable for this dataset.


## Conclusion

This project demonstrates how machine learning can be used to analyze and predict stock prices effectively. The Decision Tree Regressor’s ability to model non-linear patterns makes it particularly well-suited for this task. Future improvements could include hyperparameter optimization and the incorporation of external economic indicators to enhance predictions.


## License

This project is licensed under the MIT License. See the LICENSE file for details.


## Acknowledgments

Special thanks to Kaggle and the dataset provider for making this analysis possible.


Feel free to contribute to this repository by submitting pull requests or opening issues!
