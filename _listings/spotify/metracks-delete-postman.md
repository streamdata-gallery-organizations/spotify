{
  "info": {
    "name": "Spotify Delete My Tracks",
    "_postman_id": "0d994c0e-ea0c-4f4a-98b4-8de895ee0e3c",
    "description": "[Remove Tracks for Current User](https://developer.spotify.com/web-api/remove-tracks-user/)",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "music",
      "item": [
        {
          "id": "231ed783-4233-4772-b894-619c479ffb77",
          "name": "remove-tracks-for-current-userhttpsdeveloperspotifycomwebapiremovetracksuser",
          "request": {
            "url": "http://api.spotify.com/v1/me/tracks?ids=%7B%7D",
            "method": "DELETE",
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
            "description": "[Remove Tracks for Current User](https://developer"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8636fc0e-c455-4401-b44a-7c7e6abd8451"
            }
          ]
        }
      ]
    }
  ]
}