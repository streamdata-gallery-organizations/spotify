{
  "info": {
    "name": "Spotify Browse New Releases",
    "_postman_id": "eb73023d-c596-4cbc-baa9-b18d30bcb060",
    "description": "[Get a List of New Releases](https://developer.spotify.com/web-api/get-list-new-releases/)",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "music",
      "item": [
        {
          "id": "4359ac8f-b3df-41d2-b834-761542d80bb5",
          "name": "get-a-list-of-new-releaseshttpsdeveloperspotifycomwebapigetlistnewreleases",
          "request": {
            "url": "http://api.spotify.com/v1/browse/new-releases?country=%7B%7D&limit=%7B%7D&offset=%7B%7D",
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
            "description": "[Get a List of New Releases](https://developer"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2a0258a1-e3ba-42e1-b9cc-c08badd973cd"
            }
          ]
        }
      ]
    }
  ]
}