# data-science-application
고려대학교 데이터과학응용IV 과제

## Question 1: Underfitting Problem
* Dataset: Bike Sharing Demand
* Metric: Mean Squared Error (Best: 0)
* Description: This dataset contains historical data on bike rental counts across the years, along with several features including weather conditions, date, and time information. The relationships between the input features and the target variable (bike rental count) are non-linear and complex, making simpler models prone to underfitting.
* Project Task
  1. Goal: Your task is to predict the number of bike rentals based on the provided weather and date-time features. Initially, you will use a simple model like linear regression, which is likely to underfit this data.
  2. Instructions:
     * Begin by training a linear regression model and assessing its performance. You should observe signs of underfitting (poor training and validation performance).
     * Experiment with more complex models, such as decision trees, gradient boosting, or random forests, to better capture the underlying patterns in the data.
     * Perform feature engineering, particularly on time-related features (e.g., hour of the day, day of the week) and weather data (e.g., interactions between temperature and humidity).
  4. Labels: "count"
  

## Question 2: Feature Engineering Problem
* Dataset: POWER OVERWHELMING
* Metric: Mean Absolute Error (MAE) (Best: 0)
* Description: This dataset contains results from powerlifting competitions, including features such as age, body weight, and performance in squat, bench press, and deadlift. The data includes raw numerical features, which require extensive feature engineering to build a robust model for predicting performance.
* Project Task
  1. Goal: Your task is to predict powerlifting performance based on the various physical and competition-related features provided. The challenge here is to extract meaningful features from the raw data through extensive feature engineering.
  2. Instructions:
     * Start by exploring the dataset and identifying potential features. This may include creating new features such as ratios (e.g., weight lifted to body weight), interaction terms (e.g., age × weight), or transformations of existing features (e.g., log or polynomial transformations).
     * Perform proper handling of missing data, scaling, and normalization.
     * Train multiple models (e.g., linear regression, decision trees) on the original features and then on the newly engineered features. Compare the performance between these models.
  3. Label: "TotalKg"
