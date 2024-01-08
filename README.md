**House Price Prediction Project**

**Overview:**
Welcome to the House Price Prediction project! This project aims to predict house prices based on various features using machine learning techniques. The dataset used for this project was provided by Kaggle, and the implementation includes both Linear Regression and a Neural Network using TensorFlow/Keras.

**Dataset:**
The dataset includes columns such as 'area', 'bedrooms', 'bathrooms', 'stories', 'parking', and 'price'. The dataset was obtained from Kaggle, and you can find it here.

**Data Exploration:**
Explored the dataset's general information, summary statistics, and distribution of house prices. Visualized relationships between numeric features and the target variable using pair plots. Investigated correlations between features using a correlation matrix heatmap.

**Preprocessing:**
Handled missing values using SimpleImputer and scaled numeric features with StandardScaler. Employed ColumnTransformer and Pipeline for seamless preprocessing. Prepared the data for model training.

**Models:**
1. Linear Regression: Trained a Linear Regression model for baseline predictions and evaluated performance using Root Mean Squared Error (RMSE).

2. Neural Network (TensorFlow/Keras): Built a neural network with layers for regression. Trained the model on the dataset and evaluated its RMSE.

**Results:**
Linear Regression RMSE: 1514173.5520492247
Neural Network RMSE: 5379924.493356103
