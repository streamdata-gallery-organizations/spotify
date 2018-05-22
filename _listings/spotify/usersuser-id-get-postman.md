{
  "info": {
    "name": "Spotify Get User",
    "_postman_id": "e895b0d6-0f9b-4a85-ba39-da8bd8dfd08a",
    "description": "[Get a User's Profile](https://developer.spotify.com/web-api/get-users-profile/)",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "music",
      "item": [
        {
          "id": "b1559e6c-3667-40f4-bc81-35e620f90f18",
          "name": "get-a-users-profilehttpsdeveloperspotifycomwebapigetusersprofile",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.spotify.com",
              "path": [
                "v1",
                "users/:user_id"
              ],
              "variable": [
                {
                  "id": "user_id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "[Get a User's Profile](https://developer"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "874cbc61-3877-47fd-970a-fc6c2dbdfc2f"
            }
          ]
        }
      ]
    }
  ]
}