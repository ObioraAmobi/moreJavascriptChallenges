# Challenge. Spotify API

Create an app that:

- Allow us to search for an artist
- It should show a list of artists found
- When clicking an album it should show a list of albums
- When clicking an album it should show a list of tracks
- When clicking a track it should reproduce a preview of the song (30'')

Resources:
- __https://api.spotify.com__
    + https://developer.spotify.com/web-api/search-item/
    + https://developer.spotify.com/web-api/console/get-search-item/?q=tania+bowra&type=artist#complete

Hints: 
```
    dataType: "json"
    https://api.spotify.com/v1/search?type=artist&query=<ARTIST-NAME>
    https://api.spotify.com/v1/artists/<ID-ARTIST>/albums
    https://api.spotify.com/v1/albums/<ID-ALBUM>/tracks
```