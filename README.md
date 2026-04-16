# recipe-finder
# API Recipe Finder

## What my app does

API Recipe Finder is a web app that lets users search for real recipes using an external API. Users can search for a meal, browse recipe cards, view ingredients and instructions, get a random meal idea, and save favorite recipes.

## API used

This project uses TheMealDB API:

https://www.themealdb.com/api.php

The app uses different API endpoints to search for meals, look up recipe details, and get a random meal.

## Core features

- Search for meals by name
- Display real recipe data dynamically with JavaScript
- Show recipe cards with images, categories, and cuisine area
- Click a recipe to see ingredients and instructions
- Generate a random meal
- Save favorite recipes using localStorage
- Remove recipes from favorites
- Loading messages while data is being fetched
- Friendly error and no-results messages
- Responsive design for desktop and mobile

## Link to live site

## Screenshot

## What I learned about working with APIs

In this project, I learned how to use `fetch()` to request data from an external API. I also learned that API data comes back in JSON format, and that I need to understand the structure of the response before displaying it on the page.

I practiced using `async` and `await` to wait for the API response before updating the HTML. I also learned how to handle different situations, such as when the API is loading, when the search has no results, or when an error happens.

Another thing I learned is how to connect user input to an API call. When the user types a meal name and clicks search, the app sends that search term to TheMealDB API and then displays the matching recipes dynamically.

## Future improvements

In the future, I would like to improve the design, add filters by category or cuisine, and include more detailed recipe information. I would also like to add pagination or a better browsing feature so users can explore more recipes without searching first.
