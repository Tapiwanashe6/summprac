
# Movie Recommender App

## Table of Contents

1. [Overview](#overview)
2. [Features](#features)
3. [Demo](#demo)
4. [Technologies Used](#technologies-used)
5. [API Interaction](#api-interaction)
6. [Local Development Setup](#local-development-setup)
7. [Deployment](#deployment)
8. [Challenges and Solutions](#challenges-and-solutions)
9. [Credits and Acknowledgments](#credits-and-acknowledgments)

---

## 1. Overview

The Movie Recommender App is a web application designed to help users discover movies they might enjoy. By allowing users to filter, sort, and search through a curated list of top movies fetched from the IMDb Top 250 Movies API, the app simplifies the process of finding the perfect film.

> **Disclaimer:** This application is for educational and personal use only.

## 2. Features

### 2.1 Display Top Movies

- Shows a list of movies with their posters, titles, release years, genres, and IMDb ratings.

### 2.2 Genre Filtering

- Enables users to filter the movie list by selecting one or more specific genres (Action, Comedy, Drama, Adventure).

### 2.3 Year Filtering

- Allows users to filter movies by release year.

### 2.4 Sorting

- Sort movies by:
  - IMDb Rating (highest rated first)
  - Movie Title (alphabetical order)
  - Release Year (oldest first)

### 2.5 Searching

- Users can search movies by title or genre.

### 2.6 Refresh

- Reloads the initial shuffled list of movies.

## 3. Demo

[**Demo Video**](#) *(Add your demo video link here)*

[**Live Application**](#) *(Add your live deployment link here, if applicable)*

## 4. Technologies Used

- **Frontend:** HTML, CSS, JavaScript
- **API:** IMDb Top 250 Movies API from [RapidAPI](https://rapidapi.com/)
- **Deployment:** *(Mention deployment platform if applicable, e.g., GitHub Pages, Netlify, etc.)*

## 5. API Interaction

This application integrates with the **IMDb Top 250 Movies API** from RapidAPI to fetch and display movie data, including titles, posters, release years, genres, and ratings.

API Documentation: [IMDb Top 250 Movies API](https://rapidapi.com/imdb236/api/imdb-top-250-movies)

## 6. Local Development Setup

### Step 1: Clone the Repository

```sh
git clone [YOUR REPOSITORY URL HERE]
cd [YOUR REPOSITORY DIRECTORY NAME]
```

### Step 2: Configure API Key

Create a file named `config.js` in the root directory and add the following:

```js
const RAPIDAPI_KEY = 'YOUR_RAPIDAPI_KEY';
const RAPIDAPI_HOST = 'imdb236.p.rapidapi.com';
```

### Step 3: Open the Project

Since this is a front-end application, simply open `index.html` in a browser.

## 7. Deployment

*(Describe your deployment process. Example: GitHub Pages, Netlify, etc.)*

### If using **GitHub Pages**:

1. Ensure your project is in a public GitHub repository.
2. Go to your repository's **Settings**.
3. Navigate to **Pages**.
4. Select the branch (e.g., `main`) and deploy.
5. Your site will be available at `https://your-github-username.github.io/your-repository-name`.

## 8. Challenges and Solutions

### 8.1 API Rate Limiting

- **Issue:** Free-tier API plans have rate limits.
- **Solution:** Implemented local caching and optimized API requests.

## 9. Credits and Acknowledgments

- **IMDb Top 250 Movies API** - Provided by [RapidAPI](https://rapidapi.com/imdb236/api/imdb-top-250-movies)
- **CSS Reset:** [Meyer Reset CSS](https://cdnjs.com)

---

> **Note:** Replace placeholders (e.g., `[YOUR REPOSITORY URL HERE]`, `[YOUR LIVE APPLICATION LINK HERE]`) with actual values before deployment.

