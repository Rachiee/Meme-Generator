# Meme Generator

A simple React application that allows users to generate random meme images and overlay custom top and bottom text.

## Features

* Fetches a list of meme images from the Imgflip API.
* Displays a random meme image when the user clicks the button.
* Allows users to enter custom top and bottom text.
* Updates meme text in real time as the user types.

## How It Works

1. The app loads and fetches meme templates from the Imgflip API using `useEffect`.
2. A random meme image is selected from the fetched list when the user clicks the button.
3. Users enter top and bottom text directly into the form fields.
4. The selected image and text are displayed together in a styled meme format.

## Technologies Used

* React
* JavaScript (ES6)
* CSS (custom styling)
* Imgflip Meme API

## Getting Started

### Prerequisites

* Node.js and npm installed on your machine

### Installation

1. Clone the repository
   `git clone <your-repo-url>`

2. Navigate into the project directory
   `cd your-project-folder`

3. Install dependencies
   `npm install`

4. Start the development server
   `npm start`

## Project Structure

* `Main.jsx` handles state management, API fetching, and user interaction.
* `App.jsx` serves as the root component.
* `index.js` renders the application to the DOM.
* `styles.css` contains all layout and meme styling.

## API Reference

Imgflip Meme API
`https://api.imgflip.com/get_memes`

Returns an array of meme template objects including the image `url`.