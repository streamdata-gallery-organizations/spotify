{
  "info": {
    "name": "Spotify Get My Track Contains",
    "_postman_id": "2b484635-883b-4548-9284-430817097526",
    "description": "[Check Current User's Saved Tracks](https://developer.spotify.com/web-api/check-users-saved-tracks/)",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "music",
      "item": [
        {
          "id": "e5bf6e16-cda7-44f0-9fd5-7d8d76c54e8a",
          "name": "check-current-users-saved-trackshttpsdeveloperspotifycomwebapicheckuserssavedtracks",
          "request": {
            "url": "http://api.spotify.com/v1/me/tracks/contains?ids=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "[Check Current User's Saved Tracks](https://developer"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "82c074d0-dff3-4cfd-bc86-9c6cebb47529"
            }
          ]
        }
      ]
    }
  ]
}