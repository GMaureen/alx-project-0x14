# alx-project-0x14

# MoviesDatabase API — Documentation Summary

## API Overview
The MoviesDatabase API provides access to a large collection of movies and TV shows. You can search titles, get details (overview, release date, ratings, cast), and retrieve images/posters. It’s useful for building movie browsers or media apps.

## API Version
Current version: **v3**

## Available Endpoints
- `/search/movie` — Search movies by title or keyword  
- `/movie/{movie_id}` — Get detailed info about a movie  
- `/movie/{movie_id}/credits` — Get cast and crew info  
- `/movie/popular` — Retrieve popular movies  
- `/movie/{movie_id}/images` — Get images (posters, backdrops)

## Request and Response Format
Example search request:
