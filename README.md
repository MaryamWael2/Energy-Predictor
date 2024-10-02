# Energy Predictor 
This project focused on predicting energy usage for buildings based on historical meter readings and weather data. The project forms part of a larger effort to improve energy efficiency in buildings by enabling more accurate predictions of energy use, thereby supporting better financing and investment decisions in energy-saving retrofits.

## Project Overview

Buildings consume a significant amount of energy, and improving their efficiency is crucial for reducing costs and carbon emissions. However, it is challenging to assess the true value of energy efficiency improvements since there is no way to know how much energy a building would have used without such improvements. The aim of this project is to build counterfactual models that predict energy use based on historic meter readings and weather data. 

This model predicts energy consumption across four types of meters:
1. **Chilled Water**
2. **Electric**
3. **Hot Water**
4. **Steam**

The project utilizes a dataset spanning three years of hourly meter readings from over 1,000 buildings located across various sites globally.

## Datasets

The project uses the dataset of the **ASHRAE - Great Energy Predictor III** competition [1].

## Usage

1. Open the Jupyter Notebook `Final Project.ipynb` in the `notebooks/` folder to explore and execute the data analysis and modeling steps.
   
2. The notebook includes the following steps:
   - **Data Preprocessing**: Load and clean the data, handle missing values, and perform feature engineering.
   - **Exploratory Data Analysis (EDA)**: Visualize trends, distributions, and correlations in the data.
   - **Modeling**: Train machine learning models to predict energy consumption using historical meter readings and weather data.
   - **Evaluation**: Evaluate the model's performance using metrics such as Mean Squared Error (MSE) or Root Mean Squared Error (RMSE).

3. After training, you can adjust the hyperparameters and retrain the model to improve performance.

## Model Performance

The model's performance is evaluated based on its ability to accurately predict meter readings for the various energy types. The following metrics are used to assess the models:
- **Mean Squared Error (MSE)**
- **Root Mean Squared Error (RMSE)**

## References
[1] https://www.kaggle.com/c/ashrae-energy-prediction
