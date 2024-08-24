# Automated YouTube Playlist Downloader

The **Automated YouTube Playlist Downloader** is a web application that allows users to search for YouTube playlists by topic and download all the videos in the selected playlist. It leverages the YouTube Data API and `yt-dlp` to facilitate the search and download processes.

## Features

- **Search YouTube Playlists:** Users can search for top YouTube playlists by entering a topic or keyword.
- **Download Playlists:** Users can select a playlist from the search results and download all the videos in that playlist.
- **High-Quality Downloads:** Videos are downloaded in the best available quality using `yt-dlp`.

## Technologies Used

- **Flask:** The web framework used for building the backend of the application.
- **YouTube Data API v3:** Used to search for playlists based on a query.
- **yt-dlp:** A command-line program used to download videos from YouTube.
- **HTML/CSS:** Used for creating the frontend of the application.

## Prerequisites

- **Python 3.7+**
- **Flask:** Install using `pip install Flask`
- **google-api-python-client:** Install using `pip install google-api-python-client`
- **yt-dlp:** Install using `pip install yt-dlp`

## Getting Started

1. **Clone the repository:**

    ```bash
    git clone https://github.com/Ajaykumar-058/automated-youtube-playlist-downloader.git
    cd automated-youtube-playlist-downloader
    ```
