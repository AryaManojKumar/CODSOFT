Movie Rating Prediction 

This project predicts the rating of a movie based on features such as:
⦁	Genre
⦁	Director
⦁	Actors
⦁	Votes
⦁	Duration
⦁	Release Year
It uses regression machine learning techniques to estimate a movie’s rating from historical movie data.

1.Objective
This task demonstrates:
⦁	Data cleaning & preprocessing
⦁	Handling categorical variables (Genre, Director, Actors)
⦁	Feature selection
⦁	Model building using RandomForestRegressor
⦁	Evaluation using RMSE, MAE, R²
⦁	Plotting Actual vs Predicted values

2.Dataset
The dataset contains information such as:
⦁	Name
⦁	Year
⦁	Duration
⦁	Genre
⦁	Rating
⦁	Votes
⦁	Director
⦁	Actor

This dataset was downloaded from Kaggle and contains raw data, not preprocessed.
All necessary preprocessing steps (cleaning, encoding, numeric conversion, etc.) were handled inside the notebook.

3.Machine Learning Model Used
⦁	A Random Forest Regression model was trained using:
⦁	One-Hot Encoding (for categorical features)
⦁	StandardScaler (for numeric features where needed)
⦁	Train-test split (80% / 20%)

4.Model Performance
Metrics from evaluation:
⦁	RMSE
⦁	MAE
⦁	R² Score
These values indicate how well the model predicts movie ratings based on input features.

5.Files inside This Folder
⦁	movie_rating_notebook.ipynb	
⦁	movie_rating_model.pkl
⦁	movies.csv	
⦁	Summary.md	

6.How to Run
1.	Open the notebook movie_rating_notebook.ipynb in VS Code or Google Colab.
2.	Run all cells from top to bottom.
3.	The model will train and evaluate automatically.

7.Outputs include:
⦁	Processed dataset
⦁	Model performance metrics
⦁	Actual vs Predicted graph
