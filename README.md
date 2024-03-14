# Musical Time Machine

This project allows users to travel back in time to any specific date and create a Spotify playlist of the top Billboard 100 songs from that day. It's a perfect tool for music enthusiasts who want to reminisce about the hits from their special dates like birthdays, anniversaries, or any other significant day in history.

How It Works

The script takes a user-input date, fetches the top songs from the Billboard Hot 100 chart of that day, and then searches for these songs on Spotify. Once found, it creates a private Spotify playlist for the user containing these tracks.

Prerequisites
Before running the script, ensure you have the following installed:

Python 3
requests library
BeautifulSoup library from bs4
spotipy library
You also need a Spotify Developer account to access the Spotify API. Set up an application in your Spotify Developer Dashboard to get your client_id, client_secret, and set a redirect_uri.

