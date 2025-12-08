Movie Rating Prediction — Summary

1.Project Goal
To build a machine learning model that predicts movie ratings using features such as:
⦁	Genre
⦁	Director
⦁	Actors
⦁	Duration
⦁	Release Year
⦁	Votes

2.Data Preprocessing

⦁	The dataset from Kaggle was not preprocessed, so the following steps were performed:
⦁	Converted strings like (1996) → 1996
⦁	Extracted leading genre from multi-genre fields
⦁	Cleaned numeric columns (Duration, Votes, Year)
⦁	Encoded categorical features with OneHotEncoder
⦁	Removed rows with missing ratings

3.Modeling Approach
A Random Forest Regression model was trained.

Steps included:
⦁	Train-test split (80/20)
⦁	Transformation pipeline:
⦁	Imputation (median & most frequent)
⦁	Scaling
⦁	One-hot encoding
⦁	Model training using RandomForestRegressor

4.Evaluation metrics:
⦁	RMSE(Root Mean Square Error)
⦁	MAE(Mean Absolute Error)
⦁	R²

5.Results:

The model predicts ratings with the following approximate performance :
⦁	RMSE: ~5.3
⦁	MAE: ~3.8
⦁	R² Score: Low (because only one feature was strongly correlated)

Even though performance was limited, the model successfully demonstrates:
⦁	Feature engineering
⦁	Preprocessing real-world movie data
⦁	Regression modeling
⦁	Handling categorical variables
⦁	Evaluating predictions

Conclusion
This project fulfills the CODSOFT Task 2 requirements by building a complete Movie Rating Prediction Model using Python and machine learning.
The workflow demonstrates the entire ML pipeline from raw data, preprocessing , modeling and evaluation.
