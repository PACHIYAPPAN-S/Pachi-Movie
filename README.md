# Movie Finder

A simple web application that allows users to search for movies by title and view detailed information using the OMDb API.

## Features

- **Search for Movies:** Enter the title of a movie to fetch details.
- **Movie Details:** View information including the movie poster, genre, director, actors, plot, and IMDb rating.
- **Loading Indicator:** See a loading message while fetching data.
- **Recent Searches:** View and re-select recent search queries.

## Technologies Used

- **HTML:** Markup language for the web page.
- **CSS:** Styling for the web page.
- **JavaScript:** Manages user interactions and API requests.
- **OMDb API:** Provides movie data.

## Getting Started

To get the Movie Finder application running locally, follow these steps:

### Prerequisites

- A web browser (e.g., Chrome, Firefox).
- Internet access.

### Installation

1. **Clone the Repository**

    ```bash
    git clone https://github.com/your-username/movie-finder.git
    ```

2. **Navigate to the Project Directory**

    ```bash
    cd movie-finder
    ```

3. **Open the Application**

    Open `index.html` in your web browser by double-clicking the file or using the browser’s "Open File" option.

### API Key

To use the OMDb API, you need to provide your own API key. Replace `your_api_key_here` with your actual API key in the JavaScript code within `index.html`.

```javascript
const apiKey = 'your_api_key_here';
