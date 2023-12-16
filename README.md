# #BeastModeBot
Using Spotify's API to generate playlists on Spotify and Apple Music

For my final project in my Music as Information class, I created a playlist generator designed to create the ultimate gym playlist based on a single song. This generator requires a few things to be modified on the playlisttoken.env file. This file will contain unique access keys for Spotify, Discord, and Apple Music's APIs. The following instructions will guide you through the setup needed to run this program.

## The playlisttoken.env file

In the playlisttoken.env you will find a few blank variables that need to be filled in before running the Python notebook.

SPOTIFY_USERNAME = "Spotify Username for Account you want to link"

SPOTIFY_CLIENT_ID = "Unique client ID from Spotify Dev. Account"

SPOTIFY_CLIENT_SECRET = "Unique client secret from Spotify Dev. Account"

DISCORD_TOKEN = "Unique Discord Token if you want to run this program as a Discord Bot"

APPLE_KEY_ID = "Unique Apple Key ID from Apple Dev. Account"

APPLE_TEAM_ID = "Unique Apple Team ID from Apple Dev. Account"

Instructions on how to get your key can be found at https://github.com/therealmarius/Spotify-2-AppleMusic/blob/master/README.md
APPLE_MUSIC_KEY = "Unique Apple Dev. Account Key"


Not included in this file, but also needed to get the Apple Music generator to work is a unique account music key. This key will be pasted into the .pytnb under the variable "SECRET_KEY". It cannot be added to the playlisttoken.env file due to its format.


## The beastmode.ipynb

This file is the notebook that contains the playlist generator. There is a Spotify and an Apple section, each divided by a manual and bot option. The manual options can be run in any coding environment that supports .ipynb files. The generator will prompt the user to enter details about the search song and the artist before getting the song recommendations, sorting, and making the playlist. These playlists also have custom cover art, generated using Dall-E.
