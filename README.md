**Agricultural Crop Yield Prediction**
This project performs analysis and prediction on agricultural data related to crop production in India. The goal is to explore the dataset, visualize important insights, and build a predictive model using Random Forest Regressor to estimate crop production based on various factors.

**Table of Contents**
Project Overview
Data
Analysis
Preprocessing
Modeling
Evaluation
Visualization
Dependencies
Setup

**Project Overview**
The project involves:

**Exploratory Data Analysis (EDA)**: Visualizing the agricultural data to understand key trends, such as the distribution of agricultural area and crop production.
Data Preprocessing: Cleaning and encoding categorical variables for machine learning.
Machine Learning Model: A Random Forest Regressor is trained to predict crop production based on factors such as area, season, and district.
Evaluation: Assessing the performance of the model using metrics such as Mean Squared Error (MSE), Mean Absolute Error (MAE), and R-squared (R²).
Visualization: Scatter plots and bar plots to provide insights into the actual vs. predicted values of crop yield.
Data
The dataset contains agricultural data from various Indian states, including:

State/Union Territory
District
Crop
Year
Season
Area (Hectares)
Production (Tonnes)
Yield (Tonnes/Hectare)
The dataset contains 18,262 entries, with some missing production values.

**Key Insights**
Agricultural Area Distribution: A bar plot visualizes the top 5 Indian states with the highest agricultural area.
Crop Production Trends: Line plots visualize production trends for different states over the years.
Crop-wise Production: A bar plot highlights the total production for different crops.
Preprocessing
Categorical features (like "Crop", "Season", "State/UT") are encoded using LabelEncoder to make them suitable for machine learning models.

**Features:**
crop_encoded
season_encoded
state_encoded
District_encoded
Modeling
We use a RandomForestRegressor to build the crop production prediction model. The data is split into training and test sets.

**Model Evaluation:**
The model is evaluated using the following metrics:

Mean Squared Error (MSE): 0.043
Mean Absolute Error (MAE): 0.097
R-squared (R²): 0.958

Visualization
Scatter plots are used to compare the Actual vs. Predicted Yield values, along with a line indicating the ideal prediction.

![img3](https://github.com/user-attachments/assets/19e710c3-f3b1-49d0-8f6c-b67121f988e4)


