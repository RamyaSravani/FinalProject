# California House Price Prediction

This project aims to predict median house prices in California using a machine learning approach. The analysis uses the California housing dataset, which includes features such as geographical coordinates, housing median age, population, and median income. By leveraging this dataset, the project provides a predictive model and insights valuable for real estate forecasting.

## Abstract
The project involves:
- Data preprocessing to handle missing values.
- Exploratory Data Analysis (EDA) to derive meaningful insights.
- Development of predictive models, focusing on Linear Regression.
- Hyperparameter tuning using GridSearchCV to optimize model performance.

### Keywords
Predictive Modeling, Housing Prices, California Housing Dataset, Hyperparameter Tuning, Machine Learning.

## Dataset
The dataset was sourced from [Kaggle](https://www.kaggle.com/datasets/camnugent/california-housing-prices) and consists of:
- **Size**: 20,640 entries (California districts).
- **Features**: 
  - Numerical: Longitude, Latitude, Housing Median Age, Total Rooms, Total Bedrooms, Population, Households, Median Income.
  - Categorical: Ocean Proximity.
- **Target Variable**: Median House Value.

### Preprocessing
- Missing values in the `total_bedrooms` column were replaced with the mean.
- New features were engineered, such as `rooms_per_household`, `bedrooms_per_room`, and `population_per_household`.

## Methods
1. **Linear Regression**: A baseline model for continuous target variable prediction.
2. **Hyperparameter Tuning**: Optimization of model parameters using GridSearchCV.
3. **Feature Engineering**: Creation of derived features to enhance model performance.

### Challenges
- Balancing interpretability with model performance.
- Managing overfitting through regularization and hyperparameter tuning.

## Evaluation Metrics
- **Mean Squared Error (MSE)**: Measures average squared prediction errors.
- **Mean Absolute Error (MAE)**: Average absolute difference between predictions and actual values.
- **Root Mean Squared Error (RMSE)**: Square root of MSE.
- **R-squared (R²)**: Proportion of variance explained by the model.

### Results
- **MSE**: ~5.57 billion
- **MAE**: ~51,511.95
- **RMSE**: ~74,626.55
- **R² Score**: ~0.58

## Conclusion
The project demonstrates the application of machine learning for real estate forecasting, focusing on interpretability and feature engineering. While Linear Regression provided a strong baseline, further work can explore more complex models for better accuracy.

## References
1. [Kaggle: California Housing Prices Dataset](https://www.kaggle.com/datasets/camnugent/california-housing-prices)
2. G. James et al., "An Introduction to Statistical Learning with Applications in R," Springer, 2013.
3. T. Hastie et al., "The Elements of Statistical Learning," Springer, 2009.
4. S. Raschka and V. Mirjalili, "Python Machine Learning," Packt Publishing, 2019.
5. [Scikit-Learn Documentation](https://scikit-learn.org/stable/documentation.html)

---

Feel free to modify this README file to suit your preferences or project updates. If you'd like additional customizations, let me know!
