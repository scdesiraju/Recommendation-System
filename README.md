# Recommendation System

## Introduction
This project focuses on building various types of recommendation systems to provide personalized recommendations to users based on their preferences. The recommendation systems covered in this project include:

Content-Based Recommendation: Recommends items similar to the ones liked by the user, based on the content/features of those items.
Collaborative-Based Recommendation: Recommends items based on the preferences of users with similar tastes.
Book Recommendation: Recommends books similar to the user's favorite book, based on features like author, language, publisher, and average rating.
Movie Recommendation: Recommends movies based on the user's ratings for other movies, using collaborative filtering.
TV Show Recommendation: Recommends TV shows similar to the user's favorite TV show, using content-based filtering.

##Data Visualization
The project includes data visualization techniques to gain insights into the datasets used for recommendation. It visualizes demographic data such as age and gender distribution, as well as data related to movies, TV shows, and books.

## Content-Based Recommendation
### Movie Recommendation
Utilizes movie metadata such as keywords, cast, director, and genres.
Computes cosine similarity between movies based on these features.
Recommends movies similar to the user's input movie.
### Book Recommendation
Utilizes book metadata such as authors, language code, publisher, and average rating.
Computes cosine similarity between books based on these features.
Recommends books similar to the user's input book.
### TV Show Recommendation
Utilizes TV show metadata such as director, cast, and listed categories.
Computes cosine similarity between TV shows based on these features.
Recommends TV shows similar to the user's input TV show.

## Collaborative-Based Recommendation
### Movie Recommendation
Uses collaborative filtering to recommend movies based on user ratings.
Computes similarity between movies based on user ratings.
Recommends movies to users based on their preferences and ratings.
User Interaction
The project includes user interaction components where users can input their preferences (e.g., favorite movie, TV show, book) and receive personalized recommendations based on their inputs.

## Conclusion
This recommendation system project provides users with personalized recommendations across different domains such as movies, TV shows, and books. By leveraging various recommendation techniques, users can discover new items tailored to their tastes and preferences.
