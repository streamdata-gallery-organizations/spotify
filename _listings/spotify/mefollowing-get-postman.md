{
  "info": {
    "name": "Spotify Get Following",
    "_postman_id": "0ca6ca1b-4356-47bb-a650-0b8ea63996d0",
    "description": "[Get User's Followed Artists](https://developer.spotify.com/web-api/get-followed-artists/)",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "music",
      "item": [
        {
          "id": "28c7c550-b78b-4a3f-98d1-8679914ccf03",
          "name": "get-users-followed-artistshttpsdeveloperspotifycomwebapigetfollowedartists",
          "request": {
            "url": "http://api.spotify.com/v1/me/following?after=%7B%7D&limit=%7B%7D&type=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "[Get User's Followed Artists](https://developer"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5ab3c98f-a5da-43ea-aa3b-08eeacb9353e"
            }
          ]
        }
      ]
    }
  ]
}