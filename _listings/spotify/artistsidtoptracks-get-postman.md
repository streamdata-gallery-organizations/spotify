{
  "info": {
    "name": "Spotify",
    "_postman_id": "94fccf76-c24c-4196-a5dd-7680e1f4e4fe",
    "description": "Our Web API lets your applications fetch data from the Spotify music catalog and manage user&rsquo;s playlists and saved music. Based on simple REST principles, our Web API endpoints return metadata in JSON format about artists, albums, and tracks directly from the Spotify catalogue. The API also provides access to user-related data such as playlists and music saved in a &ldquo;Your Music&rdquo; library, subject to user&rsquo;s authorization.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "music",
      "item": [
        {
          "id": "9dc92733-0a37-4943-bcf1-a4980bd404c0",
          "name": "get-an-artists-top-trackshttpsdeveloperspotifycomwebapigetartiststoptracks",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.spotify.com",
              "path": [
                "v1",
                "artists/:id/top-tracks"
              ],
              "query": [
                {
                  "key": "country",
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
            "description": "[Get an Artist's Top Tracks](https://developer"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "56e726e2-e34d-4582-bbbe-716b2d06c06f"
            }
          ]
        }
      ]
    }
  ]
}