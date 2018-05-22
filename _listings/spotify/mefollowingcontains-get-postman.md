{
  "info": {
    "name": "Spotify Get Following contains",
    "_postman_id": "c4c9796d-0db3-4799-bf51-3ebc6ac2d5dc",
    "description": "[Check if Current User Follows Artists or Users](https://developer.spotify.com/web-api/check-current-user-follows/)",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "music",
      "item": [
        {
          "id": "75c7f55f-89ba-4cdd-9e95-13eb861115f3",
          "name": "check-if-current-user-follows-artists-or-usershttpsdeveloperspotifycomwebapicheckcurrentuserfollows",
          "request": {
            "url": "http://api.spotify.com/v1/me/following/contains?ids=%7B%7D&type=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "[Check if Current User Follows Artists or Users](https://developer"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8210335c-7cb2-49c9-9389-9e216c7cc20f"
            }
          ]
        }
      ]
    }
  ]
}