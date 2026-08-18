# Airbnb NYC Price Prediction

## Predicting Airbnb Listing Prices Using Machine Learning

## Project Overview

This project develops a machine learning solution to analyze and predict Airbnb listing prices in New York City using the AB_NYC_2019 dataset.

The project follows an end-to-end data science workflow, including data preparation, exploratory data analysis, feature engineering, preprocessing, regression modeling, model evaluation, and interpretation of results.

Because Airbnb prices contain substantial variation and extreme values, the project models log-transformed price rather than raw price. This approach reduces the influence of extreme observations and provides a more stable target for regression modeling.


## Business Problem

Airbnb hosts and marketplace stakeholders need to understand which listing characteristics are associated with pricing differences.

The project addresses questions such as:

- Which listing characteristics are associated with Airbnb prices?
- How do room type and neighborhood relate to pricing?
- Can machine learning models predict listing prices effectively?
- Which modeling approach provides the strongest predictive performance?


## Dataset

The analysis uses the New York City Airbnb Open Data (2019) dataset.

Important variables include:

1. Room type
2. Neighborhood
3. Latitude and longitude
4. Minimum nights
5. Number of reviews
6. Reviews per month
7. Availability
8. Host/listing characteristics
9. Price

The dataset represents Airbnb listings available in New York City in 2019.


## Data Preparation

The modeling workflow included:

a.	Data cleaning and preparation

b.	Handling missing numerical values using median imputation

c.	Handling missing categorical values using most-frequent imputation

d.	One-hot encoding of categorical variables

e.	Feature preparation for machine learning

f.	Log transformation of the price target

g.	Train/test model evaluation

The log transformation was particularly important because Airbnb prices contain extreme values that can disproportionately influence regression models.


## Machine Learning Models

Three regression approaches were evaluated:

•	Ridge Regression 

•	Random Forest Regression 

•	Gradient Boosting Regression 

The models were evaluated using:

•	Mean Absolute Error (MAE) 

•	Root Mean Squared Error (RMSE) 

•	R²


## Best Performing Model
The Random Forest model produced the strongest performance among the evaluated models:
•	MAE: 56.176817 
•	RMSE: 174.733429 
•	R²: 0.237391 
The results indicate that Random Forest captured more of the nonlinear relationships in the Airbnb data than the other evaluated models.

##  Verified Model Results 

| Model             |           MAE |           RMSE |           R² |
| ----------------- | ------------: | -------------: | -----------: |
| Ridge Regression  |     61.932683 |     189.027425 |     0.107518 |
| Random Forest     | **56.176817** | **174.733429** | **0.237391** |
| Gradient Boosting |     58.334163 |     186.088914 |     0.135050 |

## Key Findings
The analysis demonstrates that Airbnb pricing is influenced by multiple listing characteristics rather than a single factor. Room type, geographic location, and listing characteristics provide useful predictive information.
However, the relatively modest R² values also demonstrate that the available 2019 dataset does not explain all of the variation in Airbnb prices.


## Limitations
Important limitations include:
•	The dataset represents Airbnb listings from 2019. 

•	Market conditions and pricing behavior may have changed since the data was collected. 

•	Important variables such as current demand, seasonality, events, dynamic pricing, and economic conditions are not fully represented. 

•	Model performance is therefore more appropriate for demonstrating predictive relationships in the historical dataset than for making current-market pricing decisions. 

## Technologies
•	 Python 

•	 Pandas 

•	 NumPy 

•	 Scikit-learn 

•	 Matplotlib 

•	 Seaborn 

•	 Jupyter Notebook 

•	 Machine Learning 

•	 Regression 

•	 Feature Engineering 

## Skills Demonstrated
•	 Data Cleaning 

•	 Exploratory Data Analysis 

•	 Feature Engineering 

•	 Regression Modeling 

•	 Ensemble Learning 

•	 Model Evaluation 

•	 Data Visualization 

•	 Business Problem Framing 
•	 Responsible Interpretation of Model Results


## Project Outcome

This project demonstrates the complete process of transforming a real-world dataset into a machine learning solution while evaluating model performance and acknowledging the limitations of historical data.
