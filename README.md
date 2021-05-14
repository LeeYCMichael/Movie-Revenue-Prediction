# Movie-Revenue-Prediction
Movie Revenue Prediction Via TMDB Database (This was a joint project done with 2 other contributors)
Imagine you are a movie director and want to predict revenue. What are some things to look out for? What are some ways you can maximize the revenue earned?
The following is a model that aims to predict movie revenue via the use of the TMDB database. 
We accessed data from the TMDB database via its API.
In this model, a random forest regression model was used to realise the project statement. 
Variables such as the movies budget, movie language, movie genres, and other variables were used to predict the revenue.
The metric used to measure the accuracy of the model resulted in a R^2 value of 0.73. This meant the model was performing rather decently.
The movie performed rather well in predicting movies with high revenue. However, it over predicted revenue for movies which had low revenues.
A possible way to improve this model would have been to use a neural network for movie genres instead of the one-hot encoding used in this model. 
