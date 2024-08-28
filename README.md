# CODSOFT_INTERNSHIP TASK 1
Dealt with Titanic Dataset and predicted  the Survived and Un survived people using  Machine Learning

In this project I have taken Titanic Dataset to find  people who is survived or not using Machine learning algorithmns, by considering the target(Survived column) 
it is founded this data is a classification problem. And  data includes various features like
Passenger Id, Name, class, ticket, fare, Parch, Cabin and the target is Survived.

The initial step data pre processing, EDA, has been done and made analysis like Univariant(viewed the distributions of the data)
and found correlations and also viewed using heatmap.
Bi variant analysis(Random forest algorithm to see how target and feautures correlation)

Machine Learning algortithms used:
1. Logistic Regression
2. Random Forest
3. Socastic Gradient Descent
4. Gridsearch

Concluding: Accuracy achieved: 0.83(Randomforest and Gridsearch)

# Sales-Prediction Codsoft Task2
Dealth with Advertising dataset and predicted the Sales, This data set includes just 3 features which is a simple data,
the features are TV, Newspaper,Radio and the target is Sales,found the type of the data set is continous.
As usual I pre processed the data, done EDA(Exploratory Data Analysis), found the distributions of the features,
and splitted test train.
Used Machine Learning packages like: 
1) Linear Regression
2) Ridge
3) Lasso
4) Random Forest
Hyper Parameter Tuning: Grid search
Find the best parameter in grid search. By using Lasso Regression algorithm the accuracy was better(89%)
compared to Linear Regression it was (88%)

Concluding the Sales prediction with Acuuracy 88% (Lasso Regression, Random Forest)
  

#CODSOFT TASK 3
# IMDB-MOVIE RATING PREDICTION 

Dealt with IMDB Movie rating data, and predicted  the rating of  the movies using Machine Learning algorithms
the target in our data is Rating which is continous so it has been finalized that linear regression model will be suitable.

In this project I have taken the data of the imdb movie rating this data contains feautures like Year of the movie,
Director, Actors, Rating, Genre, Duration, Votes of the movies.
Like for all the  processing all the data I have just cleaned the data removed null found outlier and also displayed
the box plot for the outliers and for correlation I have used heatmap to display the correlation, after doing EDA process

I have done train test split and went for linear regression since the target is continous data.

Accuracy for LinearRegression is: 77%
Then used hyper parameter tuning methods like Random Forest classifier, Gradient boosting

**Percentage Error**
1. Linear regression: 22.16%
2. Gradient Boosting: 20.79%
3. Random Forest: 20.28%

Concluding the model Random forest gave the least percentage of error(20.28%)


