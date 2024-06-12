# React Fetch Posts App
This React application fetches and displays a list of posts from an external API using the fetch function. It demonstrates the use of React hooks, specifically useState and useEffect, for managing state and side effects.

## Features
* Fetches posts from the JSONPlaceholder API.
* Displays the list of posts with titles and content.
* Handles and displays errors if the data fetching fails.

## Technologies Used
* React
* JavaScript 
* HTML
* CSS

## Key Files
* src/App.js: The main component that fetches and displays posts.
* src/index.js: The entry point for the React application.
## Detailed Explanation
* App Component (src/App.js)
The App component is the core of this application. It handles the fetching of data from the JSONPlaceholder API and displays it.

## State Management
* posts: An array to store the fetched posts.
* error: A string to store any error messages encountered during data fetching.

## Side Effects
*The useEffect hook is used to perform the side effect of fetching data when the component mounts.

## Rendering
* If there is an error, it is displayed in a styled div.
* If no error, the list of posts is displayed in an unordered list (ul). Each post is shown with its title and body.
