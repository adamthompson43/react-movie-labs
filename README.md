# Assignment 1 - ReactJS app.

Name: Adam Thompson

## Overview.

This is a Node.js movie app using the TMDB API. It contains pages showing information such as popular, upcoming and top-rated movies, along with information about those movies.

### Features.
[ A bullet-point list of the __new features__ you added to the Movies Fan app (and any modifications to existing features) .]
 
+ Playlist page showing upcoming movies on the users watchlist
+ Ability to change page at bottom of each page using Pagination
+ Ability to click on the actors credited in movies, bringing the user to a google search of them
+ Top-rated movies page with ranks
+ Popular movies page with ranks

## Setup requirements.

+ Navigate to /react-movie-labs/movies
+ Type "npm start" in terminal

## API endpoints.

[ List the __additional__ TMDB endpoints used, giving the description and pathname for each one.] 

+ Discover list of movies - discover/movie
+ Movie details - movie/:id
+ Movie genres = /genre/movie/list
+ Popular movies = /movie/popular
+ Upcoming movies = /movie/upcoming
+ Top-rated movies = /movie/top_rated
+ Movie credits = /movie/credits

## Routing.

+ /movies/playlist - Shows movies that were added to the playlist
+ /movies/popular - Shows popular movies with ranking
+ /movies/topRated - Shows top-rated movies with ranking

## Independent learning (If relevant).

+ Pagination - This was used to display a page count at the bottom of each page and allow the user to change page
+ Added Rankings to popular and top rated movies, used the TMDB array for these to rank them as they were already sorted. 
+ Added links to Google search pages for the actors using the chips for the credits
