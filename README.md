# SpotifyJugaaD

## Description
SpotifyJugaaD is a Python script that allows you to download your most played and liked songs from Spotify as MP3 files from YouTube. It uses the Spotify API to fetch the user's most played and liked songs and then searches for their corresponding audio on YouTube, downloads the audio, and saves it as an MP3 file.

## Features
- Fetches the most played and liked songs from Spotify using the Spotify API.
- Searches for the corresponding audio of each song on YouTube.
- Downloads the audio from YouTube as an MP3 file and saves it in a designated folder.
- Utilizes localtunnel to expose the local server to the internet temporarily for Spotify API authentication.

## Prerequisites
- Python 3.x
- Install required Python packages using `pip`:
  ```bash
  pip install spotipy pytube pyngrok
  ```

## Getting Started
  1. Clone the repository to your local machine.
     ```bash
     git clone https://github.com/yourusername/spotify-youtube-downloader.git
     cd spotify-youtube-downloader
     ```
  2. Install the required Python packages (if you haven't already).
     ```bash
     pip install -r requirements.txt
     ```
  3. Obtain Spotify and YouTube API credentials:

  - Create a Spotify Developer account and create a new application to get SPOTIPY_CLIENT_ID and SPOTIPY_CLIENT_SECRET.
    Get your YouTube API key from the Google Developer Console.
  4. Update the API credentials and other settings in the Python script (spotify_youtube_downloader.py): 
  - Replace YOUR_SPOTIFY_CLIENT_ID, YOUR_SPOTIFY_CLIENT_SECRET, YOUR_YOUTUBE_API_KEY, and YOUR_REDIRECT_URI with your actual credentials.
  5. Run the script to download your favorite songs from Spotify as MP3 files.

      ```bash
      pip install spotipy pytube pyngrok
      ```
## Configuration
  - You can modify the following settings in spotify_youtube_downloader.py:
  - limit: Number of most played and liked songs to fetch from Spotify.
  - output_folder: Folder where downloaded MP3 files will be saved.

## Acknowledgments
  - This project uses the spotipy library for interacting with the Spotify API.
  - It also uses the pytube library for downloading YouTube videos.
  - The temporary public URL is generated using localtunnel.
## Disclaimer
  This project is intended for personal use only. Please make sure to comply with the terms of service of Spotify and YouTube when using this script.
  
  Happy downloading!
