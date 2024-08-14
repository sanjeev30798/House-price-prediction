# House price prediction
This repository contains the implementation of a house price prediction model using the CatBoost algorithm. The model predicts house prices in different cities based on several factors including area, locality, layout, and furnish type.

Overview
Accurately predicting house prices is essential for real estate planning, investment, and decision-making. This project aims to create a robust model that can predict house prices across various cities with a high degree of accuracy. The model was trained using the CatBoost algorithm, which is particularly effective for handling categorical features and complex relationships within the data.

Model Performance
R² Score: 0.82
Root Mean Squared Error (RMSE): 5793.97
Prediction Accuracy
The model was able to predict house prices with a significant degree of accuracy:

92% of test data points fall within a range of -30% to +30% of the actual prices.
This range is considered acceptable for this model, particularly for cases where certain unique combinations of features (e.g., specific locality and furnish type) had no direct records in the training data. In such cases, predictions are made based on the closest available data points. The model is expected to improve as more data points for these unique combinations are added to the training set.

Features Used
The model predicts house prices based on the following features:

Area: The size of the house.
Locality: The geographical location or neighborhood.
Layout: The structural layout of the house (e.g., number of rooms, floor plan).
Furnish Type: The furnishing status of the house (e.g., fully furnished, semi-furnished, or unfurnished).
