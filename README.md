# DVD Rental Duration Prediction Project

## Overview

This project aims to assist a DVD rental company in predicting the duration for which a customer will rent a DVD. By achieving this, the company can optimize its inventory planning and enhance efficiency. The goal is to develop regression models that predict rental duration with a Mean Squared Error (MSE) of 3 or less on a test set.

## Data Description

The provided dataset `rental_info.csv` includes the following features:

- `"rental_date"`: Date and time of DVD rental.
- `"return_date"`: Date and time of DVD return.
- `"amount"`: Rental cost paid by the customer.
- `"amount_2"`: Square of the rental cost.
- `"rental_rate"`: Rate at which the DVD is rented.
- `"rental_rate_2"`: Square of the rental rate.
- `"release_year"`: Year of movie release.
- `"length"`: Length of the movie in minutes.
- `"length_2"`: Square of the movie length.
- `"replacement_cost"`: Cost to replace the DVD.
- `"special_features"`: Additional features like trailers or deleted scenes.
- `"NC-17"`, `"PG"`, `"PG-13"`, `"R"`: Dummy variables for movie ratings.

## Project Tasks

### Data Preprocessing
- Loaded and cleaned the data, handling missing values and data types.
- Engineered features where necessary to enhance model performance.

### Exploratory Data Analysis
- Conducted an analysis to understand the distribution and relationships among various features.
- Visualized key aspects to gain insights relevant for modeling.

### Model Development
- Built and evaluated several regression models to predict DVD rental duration.
- Tuned models to achieve the target MSE of 3 or less on the test set.
- Selected the best-performing model based on evaluation metrics.

### Model Evaluation and Selection
- Assessed models based on MSE and other relevant metrics.
- Performed cross-validation to ensure the model's generalizability.

### Results and Recommendations
- Summarized findings and provided recommendations for inventory planning based on rental duration predictions.
- Suggested further improvements and potential areas for future analysis.

## Technologies Used
- Data analysis and preprocessing: `pandas`, `numpy`
- Machine learning modeling: `sklearn`
- Data visualization: `matplotlib`, `seaborn`


## Contributors
- Danial Rashid Inam

*This project provides actionable insights for the DVD rental company, enabling more effective and efficient inventory management through predictive analytics.*
