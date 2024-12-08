# Project Overview
This project focuses on predicting house prices in Poland based on various features such as size, location, and number of bedrooms. The goal is to build a regression model that can accurately predict the price of a house from these features.

## Dataset:
- **Source**: [House Prices in Poland Dataset](https://www.kaggle.com/datasets/dawidcegielski/house-prices-in-poland/data)
- **Availability**: Also included in the project’s Git repository.
- The dataset contains information on house prices, locations, sizes, and other features.

## Goal:
- Predict house prices based on features such as location, size, number of rooms, and more.
- Analyze the impact of city and other attributes on house pricing trends.

---

### Note:
This project is inspired by the tutorial:  
[NeuralNine - House Price Prediction Tutorial](https://www.youtube.com/watch?v=Wqmtf9SA_kk&t=1728s&ab_channel=NeuralNine).

## Key Steps
### 1. Data Preprocessing and EDA

### 2. Model Training
- **Features**: Selected features like square footage, number of bedrooms, year built, and location.
- **Model**: Used `RandomForestRegressor` for predictions with hyperparameter tuning using GridSearchCV.
- **Performance:**:
    - Accuracy: **78%**
    - `n_estimators=50`, `max_depth=10`, `min_samples_split=5`, `min_samples_leaf=1`

### 3. Feature Importance Analysis
- **Feature Importance**: Analyzed the importance of features in the prediction using `RandomForestRegressor`. The most important features were square footage, year built, and location, with some features contributing less than 0.1 to the model.

### 4. Model Analysis and Visualization

## Conclusion
Overall, the Random Forest model perfor (78% of accuracy)ms well, but there is still room for improvement, particularly for higher-priced homes or certain unusual data points. These outliers might be addressed by tuning the model further or using additional features.