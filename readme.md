# Tunisian Car Price Prediction



## Overview
This project focuses on predicting car prices in Tunisia using various machine learning and deep learning techniques. By leveraging data from a dataset containing key features about cars in Tunisia, such as car make, model, mileage, engine size, and more, we aim to build a model that accurately predicts the price of a used car. The project begins with Exploratory Data Analysis (EDA) to better understand the trends and relationships between features and the car prices.

Through the analysis, we uncovered two major findings regarding the used car market in Tunisia:

- **Price and Demand** : Lower-priced cars tend to be in higher demand than expensive cars. However, there is still a niche market for luxury cars, with brands like Land Rover, Jaguar, and Porsche being sought after by specific customer segments.


- **Car Preferences:** : The majority of cars in Tunisia run on petrol and diesel, with a few hybrid models. The most popular car colors are black, white, and grey, and the most demanded body styles include 4x4 and pickup models.


The main objective of this project is to predict the price of a car based on various features, and the results are compared using machine learning and deep learning models. Several models were applied to the dataset, including Decision Tree Regressor and Random Forest Regressor. After evaluating the models, it was found that the Random Forest Regressor outperformed the Decision Tree Regressor in terms of accuracy and reliability.

## Dataset Features
| Column Name         | Description                                                                 |
|---------------------|-----------------------------------------------------------------------------|
| **Location**        | The location of the car in Tunisia                                           |
| **time_posted**     | The time when the car was posted for sale                                    |
| **Mileage**         | The mileage of the car in kilometers                                        |
| **vehicle_color**   | The color of the car                                                         |
| **vehicle_condition**| The condition of the car (new or used)                                      |
| **engine_size**     | The engine size in liters                                                   |
| **year**            | The manufacturing year of the car                                           |
| **gearbox**         | The type of gearbox (Automatic or Manual)                                   |
| **brand**           | The brand of the car                                                         |
| **model**           | The specific model of the car                                               |
| **car_body**        | The body type of the car (e.g., SUV, Pickup, Sedan)                         |
| **fuel**            | The fuel type of the car (e.g., Petrol, Diesel, Hybrid)                     |
| **horsepower**      | The car’s horsepower (CV)                                                   |
| **price**           | The target variable - the price of the car in Tunisian Dinars (TND)         |


## Conclusion
In this project, we have explored the factors influencing the car market in Tunisia, including preferences for car type, engine specifications, and colors. Our analysis highlights that lower-priced cars dominate the market, but there is still a significant demand for luxury cars among a niche group of consumers. Cars with higher performance, particularly 4x4 and pickup models, are also more sought after.

We implemented several machine learning algorithms to predict car prices. The Random Forest Regressor model demonstrated superior performance compared to the Decision Tree Regressor, likely due to its ability to handle overfitting and capture more complex relationships in the data. Although the model's performance is satisfactory, there is always room for further improvement through hyperparameter tuning, feature engineering, or the incorporation of more advanced techniques like deep learning models.

This analysis can provide valuable insights for car dealers and buyers in Tunisia, allowing them to make more informed decisions based on car features and market trends.


