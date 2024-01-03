# Housing Price Prediction

This Python script predicts housing prices using machine learning techniques. It combines the power of XGBoost and a Deep Neural Network (DNN) for regression tasks. The script also includes data preprocessing steps to clean and prepare the dataset.

## Overview

1. Loads training and testing data from CSV files: `Stat_380_train2021.csv` and `Stat_380_test2021.csv`.

2. Applies data preprocessing, handling missing values, and feature selection.

3. Trains two models: an XGBoost Regressor and a Deep Neural Network using TensorFlow/Keras.

4. Combines predictions from both models to generate a final submission CSV file named `submission.csv` containing housing price predictions.

## How to Use

1. Place the `Stat_380_train2021.csv` and `Stat_380_test2021.csv` files in the same directory as the script.

2. Run the script:

   ```shell
   python housing_price_prediction.py
