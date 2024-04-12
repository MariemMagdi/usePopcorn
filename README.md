# usePopcorn 🍿

**usePopcorn** is a React web application for movie enthusiasts to search, view, and manage a personal list of watched movies with custom ratings. Utilizing a modern React stack including hooks for state and effects, this project demonstrates a practical use-case of integrating APIs, managing local storage, and handling user interactions in a scalable way.


## Features

- **Search Functionality**: Search for movies using the OMDb API.
- **Interactive Lists**: Display movies based on search results and manage a personal "watched movies" list.
- **Custom Hooks**: Includes custom hooks like `useMovies`, `useLocalStorageState`, and `useKey` to encapsulate various functionalities.
- **Local Storage Integration**: Persist your watched movies list and ratings between sessions.
- **Dynamic Movie Details**: View details of each movie and add them to your watched list with personal ratings.

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/usePopcorn.git
   ```
2. Navigate to the project directory:
   ```bash
   cd usePopcorn
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Run the application:
   ```bash
   npm start
   ```

## Usage

Start the application and use the search bar to find movies. Click on any movie to view its details, add it to your watched list, or rate it. Manage your watched movies and view summary statistics such as average IMDb rating, user rating, and average runtime directly from your dashboard.

## Technologies

- React (Hooks)
- Local Storage for persistent data management
- OMDb API for movie data

