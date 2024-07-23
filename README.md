# Movie Library

A simple movie library application built with HTML, Bootstrap, and JavaScript to manage and display a collection of movies. This project uses JavaScript classes to encapsulate functionality and manage the application state.

## Table of Contents
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Technologies Used](#technologies-used)
- [License](#license)

## Features
- Add new movies with details such as name, director, year, type, and image.
- Edit existing movies.
- Delete movies from the list.
- Filter movies by genre.
- Display a list of movies in a responsive grid.

## Installation
1. Clone the repository,
2. Navigate to the project directory:
    ```bash
    cd movielibrary
    ```

## Usage
1. Open `index.html` in your browser:
    ```bash
    open index.html
    ```
2. Use the form on the left side of the screen to add new movies.
3. Movies will be displayed on the right side and in the movie list below.
4. Use the filter buttons to filter movies by genre.
5. Edit or delete movies using the options in the dropdown menu on each movie card.

## Project Structure
movielibrary/
│
├── index.html
├── movie.js
├── movieList.js
├── ui.js
└── README.md


- `index.html`: The main HTML file containing the structure of the webpage.
- `movie.js`: Defines the `Movie` class.
- `movieList.js`: Contains the `MovieList` class for managing the list of movies.
- `ui.js`: Contains the `UI` class for handling the user interface.
- `README.md`: Documentation for the project.

## Technologies Used
- HTML
- CSS
- Bootstrap 5
- JavaScript

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
