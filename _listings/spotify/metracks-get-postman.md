{
  "info": {
    "name": "Spotify Get My Tracks",
    "_postman_id": "9b7caad4-c06d-4de9-9d77-168ebe25c770",
    "description": "[Get Current User's Saved Tracks](https://developer.spotify.com/web-api/get-users-saved-tracks/)",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "music",
      "item": [
        {
          "id": "5e52c7ec-df91-443e-94c4-cb33c49503f3",
          "name": "get-current-users-saved-trackshttpsdeveloperspotifycomwebapigetuserssavedtracks",
          "request": {
            "url": "http://api.spotify.com/v1/me/tracks?limit=%7B%7D&market=%7B%7D&offset=%7B%7D",
            "method": "GET",
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
            "description": "[Get Current User's Saved Tracks](https://developer"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1d90efeb-08d8-4987-92a0-66b1f3c1d7e3"
            }
          ]
        }
      ]
    }
  ]
}