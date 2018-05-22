{
  "info": {
    "name": "Spotify Delete Following",
    "_postman_id": "4d6a0864-338f-4ee8-b36d-c27ed3a53881",
    "description": "[Unfollow Artists or Users](https://developer.spotify.com/web-api/unfollow-artists-users/)",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "music",
      "item": [
        {
          "id": "c1040e13-5b32-4efd-9dcb-d2713ee5cc1e",
          "name": "unfollow-artists-or-usershttpsdeveloperspotifycomwebapiunfollowartistsusers",
          "request": {
            "url": "http://api.spotify.com/v1/me/following?ids=%7B%7D&type=%7B%7D",
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "[Unfollow Artists or Users](https://developer"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "264d9733-56b8-4773-87b9-73c50cd05f29"
            }
          ]
        }
      ]
    }
  ]
}