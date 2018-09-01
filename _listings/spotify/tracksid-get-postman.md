{
  "info": {
    "name": "Spotify Get Track",
    "_postman_id": "7a4bbe7e-be4f-4ae9-9645-25b139bcf15b",
    "description": "[Get a Track](https://developer.spotify.com/web-api/get-track/)",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "music",
      "item": [
        {
          "id": "3d1f01ac-6047-4c10-9eda-d0db7a51374d",
          "name": "get-a-trackhttpsdeveloperspotifycomwebapigettrack",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.spotify.com",
              "path": [
                "v1",
                "tracks/:id"
              ],
              "query": [
                {
                  "key": "market",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "[Get a Track](https://developer"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "db00ba17-ec63-4379-bb69-4489462f2305"
            }
          ]
        }
      ]
    }
  ]
}