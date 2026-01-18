# Computer-Vision-Beginner-project
# Predictive-Modeling-of-Urban-Air-Quality

Predictive Modeling of Urban Air Quality

This project is focusing on development of a machine learning framework to forecast air quality levels in urban environments. By analyzing historical sensor data and various meteorological conditions, our model can predict concentrations of pollutants such as PM2.5​ and NO2​ with high accuracy. Air pollution is becoming a critical issue for modern city, and this repository provides a complete pipeline for data preprocessing and predictive modeling. We use environmental factor like temperature, humidity, and wind speed to improve the final prediction results.

The dataset consist of hourly measurements from urban monitoring stations and includes pollutant levels like PM2.5​ and CO, along with weather data and temporal timestamps for every observation recorded. All data's used in this project are collected from public environmental APIs and preprocessed for easier use in the training scripts.

To get started with this project on your local machine, you should first clone the repository using the git clone command and then install the dependencies list with pip install -r requirements.txt. Once your environment is ready, place your raw CSV files in the data folder before to run the scripts. You can start the training process by executing python AirQualityProject/train_model.py, which will process the data and save the trained model in the models directory. To see the prediction results on the test set, you can run the evaluation notebook.

Our current model reach a Mean Absolute Error (MAE) of 12.5 for PM2.5​ predictions, and we found that wind speed is the most important feature to determine how pollutants are dispersed in the city area. Future work will include the integration of Deep Learning (LSTM) to handle long-term dependencies in the air quality data.
