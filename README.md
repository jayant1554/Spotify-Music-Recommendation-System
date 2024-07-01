# Spotify Music Recommender

This project is a Spotify song recommendation system built using the Spotify API. It takes user playlists and song input to suggest songs. The user can specify the number of songs they want to be recommended, and it is deployed locally using Flask.

## Table of Contents
- [Installation](#installation)
- [Features](#features)
- [Contributing](#contributing)
- [Contact](#contact)

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/jayant1554/spotify-music-recommender.git
    cd spotify-music-recommender
    ```

2. Create and activate a virtual environment:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

4. Set up your Spotify API credentials. Create a `.env` file in the root directory of the project and add your Spotify API client ID and secret:
    ```env
    SPOTIPY_CLIENT_ID='your-spotify-client-id'
    SPOTIPY_CLIENT_SECRET='your-spotify-client-secret'
    SPOTIPY_REDIRECT_URI='your-redirect-uri'
    ```


## Features

- **User Input**: Accepts user playlists or specific song input for generating recommendations.
- **Recommendations**: Provides a specified number of song recommendations based on the input.
- **Deployment**: Runs locally using Flask.

## Contributing

Contributions are welcome! If you have any ideas, suggestions, or issues, feel free to open an issue or submit a pull request
## Contact

If you have any questions or need further assistance, you can contact me via:

- GitHub: [@jayant1554](https://github.com/jayant1554)
- Email: jk913600@gmail.com
