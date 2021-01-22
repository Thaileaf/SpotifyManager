# SpotifyManager
Save, restore, and delete Spotify Playlists as JSON files

Libraries to install: requests, spotipy, PyQt5

This program requires Spotify Developer keys that you can get from creating a Spotify app as a developer. Create a spotifySettings.json file and make a dictionary with the keys "client" and "secret". Make the values your client and secret keys from the spotify APP. Go to your Spotify App and have a http://localhost:8888 redirect uri.

WARNING: 
-Do not press the delete playlist button without first backing up. It will delete ALL playlists
-Restored playlists do not order songs by date, so if you restore playlists it will mess up this order
