# Movie-IMDB-Score-Predictions

# Movie IMDb Score Prediction

This project explores the IMDb score prediction for movies using machine learning techniques. It involves data exploration, data cleaning, and building a predictive model.

## Overview

The goal of this project is to develop a machine learning model that predicts the IMDb score of movies. The IMDb score is an important metric for evaluating the quality and popularity of movies. By predicting IMDb scores, we can provide insights into the potential success of upcoming movies and help decision-makers in the film industry.

## Data

The dataset used in this project contains information about various movies and shows, including features such as age_certifiaction, release_year, production_coubtries, seasons, genre, and runtime. The target variable is the IMDb score, which ranges from 0 to 10. The dataset was obtained from Kaggle and contains over 5000 number of observations, that is, movies and shows.

## Workflow

1. **Data Exploration**: The dataset was explored to understand the count of unque values in each features, identify missing values, and so on. Visualizations were used to gain insights into the relationships between different features and the IMDb score. Specifically, to check if there is a relationship between the imdb_votes and the Imdb_score. 

2. **Data Cleaning**: Data cleaning involved handling missing values, deleting columns that has a lot of  null values(over 50%), dropping column leakeges, columns with high cardinality and multicolineraity. 

3. **Model Building**:  The dataset was split into training and testing sets. The model built is a Ridge Regression model. Considering the features and the target, the Ridge Regression was used.

4. **Model Evaluation**: The performance of the trained model was evaluated using the metric, mean absolute error (MAE).

5. **Prediction**: The final model was used to predict the IMDb scores of movies for which IMDb scores were not available. These predictions can provide valuable insights for decision-making in the film industry. 


## Conclusion

In conclusion, this project demonstrates the process of predicting IMDb scores for movies using machine learning techniques. By exploring the data, cleaning it, and building a predictive model, valuable insights can be gained into the factors that influence the IMDb score of movies. These insights can be used by stakeholders in the film industry to make informed decisions and enhance the quality and success of future movie releases.


- Special thanks to Kaggle for providing the dataset used in this project.
