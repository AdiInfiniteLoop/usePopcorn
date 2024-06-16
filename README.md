# usePopcorn - Movie Tracking App

usePopcorn is a React application that allows users to search for movies, view movie details, and keep track of the movies they've watched. It utilizes the OMDb API to fetch movie data and provides a user-friendly interface for managing and rating movies.

## Features

- **Movie Search**: Users can search for movies by entering a query in the search bar.
- **Movie Details**: Clicking on a movie from the search results displays detailed information about the movie, including the title, year, runtime, plot, cast, and rating.
- **Add to Watched List**: Users can rate a movie and add it to their watched list with a single click.
- **Watched Movie Summary**: The app provides a summary of the watched movies, including the average IMDb rating, average user rating, and average runtime.
- **Remove from Watched List**: Users can easily remove a movie from their watched list.
- **Keyboard Navigation**: The app supports keyboard navigation, allowing users to close the movie details view by pressing the "Escape" key.

## Technologies Used

- React
- Custom Hooks (e.g., `useMovies`, `useLocalStorage`, `useKey`)
- Fetch API
- OMDb API

## Installation

1. Clone the repository: `git clone https://github.com/your-username/usePopcorn.git`
2. Navigate to the project directory: `cd usePopcorn`
3. Install dependencies: `npm install`
4. Start the development server: `npm start`

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
