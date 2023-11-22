## Useage

### 1. Change config.ini

```
# config.ini

[client]
name = your_spotify_name
client_id= your_cliend_id
client_secret = your_client_secret

[oauth]
scope = user-read-playback-state
redirect_uri = your_redirect_uri
sp_dc = your_sp_dc

[app] # No need to change it. Optional change
app_name = spotify_lyrics
app_logo = ./assets/icon.jpg

```

- cliend_id, client_secret,
- sp_dc can get from your cookie in https://open.spotify.com/

### 2. excute 'spotify lyrics overlay.exe'

#

The project was built with pyinstaller
