# Experience-with-salary-prediction
Predicting salary from years of experience using Linear Regression and evaluating the model on test data.
Salary Prediction with Linear Regression — Project Description
In this project, I used a dataset of 40 records with two columns: Experience Years and Salary. My goal was to predict salary based on years of experience.

I first explored the dataset using head(), tail(), shape, info(), and describe(). I also checked for missing values and duplicate rows and found none. A scatter plot showed that salary generally increases as experience increases.

I defined Experience Years as the input feature (X) and Salary as the target (y). I first trained a Linear Regression model on the full dataset to understand its prediction line. Then I split the data into 32 training rows and 8 test rows, trained a new model, and used it to predict salaries for the test rows.

I compared the predicted salaries with the actual salaries in a table and a graph. On the test set, the model achieved an MAE of approximately 6,420, an RMSE of approximately 6,934, and an R² of approximately 0.907. The MAE means its predictions differed from the actual salaries by about 6,420 salary units on average across those eight test rows.

This project helped me practice the complete basic workflow: exploring data, defining a feature and target, training a model, making predictions, and evaluating the results on separate test data.
