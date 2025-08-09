# alx-project-0x14

## API Overview

The MoviesDatabase API provides access to a vast collection of movie-related data including movies, TV shows, actors, genres, and user reviews. It allows developers to search for titles, retrieve detailed information, and access trending and popular media. The API supports filtering, sorting, and pagination to help efficiently query large datasets.

## Version

The current version of the MoviesDatabase API is **v1.0**.

## Available Endpoints

- **GET /movies**  
  Retrieve a list of movies with optional filters such as genre, year, and rating.

- **GET /movies/{id}**  
  Fetch detailed information about a specific movie by its ID.

- **GET /actors/{id}**  
  Get information about a particular actor, including filmography.

- **GET /genres**  
  List all available movie genres.

- **GET /reviews/{movie_id}**  
  Retrieve user reviews for a specific movie.

- **POST /auth/login**  
  Authenticate a user and receive an API token.

## Request and Response Format

### Request

API requests are typically made via HTTPS with parameters passed as query strings for GET requests or as JSON in the request body for POST requests.

Example GET request to fetch movies:
