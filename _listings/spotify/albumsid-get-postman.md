{
  "info": {
    "name": "Spotify",
    "_postman_id": "7fef8eeb-2c2b-45b7-9fc1-aef2f6a18916",
    "description": "Our Web API lets your applications fetch data from the Spotify music catalog and manage user&rsquo;s playlists and saved music. Based on simple REST principles, our Web API endpoints return metadata in JSON format about artists, albums, and tracks directly from the Spotify catalogue. The API also provides access to user-related data such as playlists and music saved in a &ldquo;Your Music&rdquo; library, subject to user&rsquo;s authorization.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "music",
      "item": [
        {
          "id": "ac9da4c8-302e-4f22-9865-97ed15c35271",
          "name": "get-an-albumhttpsdeveloperspotifycomwebapigetalbum",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.spotify.com",
              "path": [
                "v1",
                "albums/:id"
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
            "description": "[Get an Album](https://developer"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9ef756bf-ac4d-4bec-a83a-eaabf15a49c3"
            }
          ]
        }
      ]
    }
  ]
}