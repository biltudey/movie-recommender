
# **Building And Deploying A Movie Recommender System**

Content Based Recommender System recommends movies similar to the movie user likes and analyses the sentiments on the reviews given by the user for that movie.

The details of the movies(title, genre, runtime, rating, poster, etc) are fetched using an API by TMDB, https://www.themoviedb.org/documentation/api, and using the IMDB id of the movie in the API. 

We use *web scraping* to get the reviews given by the user in the IMDB site using beautifulsoup4 and performed sentiment analysis on those reviews.
## Running Flask Tests

To run a Flask deployment tests, run the following command

```bash
  python main.py
```


## Running Heroku Tests

To run a The application, click on the following link:

https://moviesrecommendationapp.herokuapp.com/








![logo](https://github.com/MrBriit/Netflix-Recommender-System-and-Deployment/blob/main/net%20screenshot.png?raw=true)


