{
  "info": {
    "name": "Spotify Update My Tracks",
    "_postman_id": "f2497b53-ac15-4db4-93a7-fe7d516ac133",
    "description": "[Save Tracks for Current User](https://developer.spotify.com/web-api/save-tracks-user/)",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "music",
      "item": [
        {
          "id": "d3abfec5-502c-4f6e-806d-7488460b3ab7",
          "name": "save-tracks-for-current-userhttpsdeveloperspotifycomwebapisavetracksuser",
          "request": {
            "url": "http://api.spotify.com/v1/me/tracks?ids=%7B%7D",
            "method": "PUT",
            "header": [
              {
                "key": "Accept",
                "value": "{}",
                "description": "It is used to set specified media type",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "[Save Tracks for Current User](https://developer"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "201fef06-68d4-4669-8b04-2b94e3c3c498"
            }
          ]
        }
      ]
    }
  ]
}