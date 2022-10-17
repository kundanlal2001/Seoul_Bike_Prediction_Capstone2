# Seoul_Bike_Prediction_Capstone2

We Chose this topic as there was much with which we can correlate from real world scenario , also as in most of the big cities of India few new emerging bike renting companies are also starting businesses ,so we thought it would be really interesting to check their world of demand and factors affecting their  demand .
We have done this project from a perspective that any Bike renting company has asked us as a Data Scientist to find the number of bike predictions based on all these independent variables as historic data given by them.
Going ahead we first cleaned the dataset having 8760 rows & 14 columns and applied 1 hot encoding on some independent categorical variables to be able to push them into machine learning, 

Via EDA we also independently checked the collinearity of all independent variables with the dependent variables one by one and gathered findings from them,
Then we checked the distribution pattern of all these independent variables and thereafter just before pushing data into our model we checked multi collinearity  using Heat map and dropped the highly multi collinear variables and other unimportant columns,
Post that we did splitting of our dataset into Train and Test set by assigning ratio and then,

We have run ML Model using multiple algorithms like :-

Linear Regression
Decision Tree
Random Forest 
Elastic net Regression

And found out Metrics like :- 
R2 ,
Adjusted R2
RMSE,
MSE ,
MAE
For them .



