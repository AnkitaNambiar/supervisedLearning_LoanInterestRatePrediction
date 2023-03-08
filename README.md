# supervisedLearning_LoanInterestRatePrediction
In Python, I conducted feature and model engineering to predict Loan Interest Rates from a dataset of 400k rows. The project was conducted for a UChicago Analytics class. Do not duplicate. 

# Overview of Process

In the Loan Interest Rate Prediction Project, I utilized many data cleaning and machine learning methods, including:

- K-nearest neighbor imputation

- discretization of continuous variables

- dummy variable creation

- standardization through a scaler

- Root mean square error (RMSE) scoring (for continuous target a variable)

- Cross-Validation Scoring

- inverse standardization. 

I also created a feature importance graph, as seen below. 
<img width="725" alt="Screenshot 2023-02-23 at 12 35 04 AM" src="https://user-images.githubusercontent.com/105748980/220835666-98349e9f-9e37-4d49-a647-ddafc6995e5c.png">

I evaluated my cleaned training data frame with the following Machine Learning models:

- Decision Tree Regression

- Linear Regression

- Random Forest Regression

- Gradient Boosting Regression

I ended up choosing Random Forest Regression for modeling my training data and predicting the Loan Interest Rate since it received the lowest RMSE of 0.08632, which is very low and very promising. 

I also made sure to check overfitting and underfitting, so I ran the Cross-Validation scorer and got an RMSE of 0.1005, which is very close to the 0.08632 RMSE. Due to the very low and good RMSE’s of both and their close similarity, I did not have to worry about fixing the overfitting/ underfitting of the model. 

After cleaning and fitting the testing dataset to the Random Forest Regression model, I was able to make data-driven predictions for the testing dataset’s Loan Interest Rates. 





