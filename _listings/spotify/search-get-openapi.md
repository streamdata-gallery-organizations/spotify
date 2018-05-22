---
swagger: "2.0"
x-collection-name: Spotify
x-complete: 0
info:
  title: Spotify Search
  description: '[Search for an Item](https://developer.spotify.com/web-api/search-item/)'
  version: v1
host: api.spotify.com
basePath: /v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /albums:
    get:
      summary: Get Albums
      description: '[Get Several Albums](https://developer.spotify.com/web-api/get-several-albums/)'
      operationId: get-several-albumshttpsdeveloperspotifycomwebapigetseveralalbums
      x-api-path-slug: albums-get
      parameters:
      - in: query
        name: ids
        description: A comma-separated list of IDs
      - in: query
        name: market
        description: The market (an ISO 3166-1 alpha-2 country code)
      responses:
        200:
          description: OK
      tags:
      - Music
      - Albums
  /albums/{id}:
    get:
      summary: Get Album
      description: '[Get an Album](https://developer.spotify.com/web-api/get-album/)'
      operationId: get-an-albumhttpsdeveloperspotifycomwebapigetalbum
      x-api-path-slug: albumsid-get
      parameters:
      - in: path
        name: id
        description: The Spotify ID for the album
      - in: query
        name: market
        description: The market (an ISO 3166-1 alpha-2 country code)
      responses:
        200:
          description: OK
      tags:
      - Music
      - Albums
  /albums/{id}/tracks:
    get:
      summary: Get Album Tracks
      description: '[Get an Album''s Tracks](https://developer.spotify.com/web-api/get-albums-tracks/)'
      operationId: get-an-albums-trackshttpsdeveloperspotifycomwebapigetalbumstracks
      x-api-path-slug: albumsidtracks-get
      parameters:
      - in: path
        name: id
        description: The Spotify ID for the album
      - in: query
        name: limit
        description: The maximum number of items to return
      - in: query
        name: market
        description: The market (an ISO 3166-1 alpha-2 country code)
      - in: query
        name: offset
        description: The index of the first item to return
      responses:
        200:
          description: OK
      tags:
      - Music
      - Album
      - Tracks
  /artists:
    get:
      summary: Get Artists
      description: '[Get Several Artists](https://developer.spotify.com/web-api/get-several-artists/)'
      operationId: get-several-artistshttpsdeveloperspotifycomwebapigetseveralartists
      x-api-path-slug: artists-get
      parameters:
      - in: query
        name: ids
        description: A comma-separated list of IDs
      responses:
        200:
          description: OK
      tags:
      - Music
      - Artists
  /artists/{id}:
    get:
      summary: Get Artist
      description: '[Get an Artist](https://developer.spotify.com/web-api/get-artist/)'
      operationId: get-an-artisthttpsdeveloperspotifycomwebapigetartist
      x-api-path-slug: artistsid-get
      parameters:
      - in: path
        name: id
        description: The Spotify ID for the artist
      responses:
        200:
          description: OK
      tags:
      - Music
      - Artists
  /artists/{id}/albums:
    get:
      summary: Get Artist Albums
      description: '[Get an Artist''s Albums](https://developer.spotify.com/web-api/get-artists-albums/)'
      operationId: get-an-artists-albumshttpsdeveloperspotifycomwebapigetartistsalbums
      x-api-path-slug: artistsidalbums-get
      parameters:
      - in: query
        name: album_type
        description: Filter by album types
      - in: path
        name: id
        description: The Spotify ID for the artist
      - in: query
        name: limit
        description: The maximum number of items to return
      - in: query
        name: market
        description: The market (an ISO 3166-1 alpha-2 country code)
      - in: query
        name: offset
        description: The index of the first item to return
      responses:
        200:
          description: OK
      tags:
      - Music
      - Artists
      - Albums
  /artists/{id}/related-artists:
    get:
      summary: Get Artist Related ARtists
      description: '[Get an Artist''s Related Artists](https://developer.spotify.com/web-api/get-related-artists/)'
      operationId: get-an-artists-related-artistshttpsdeveloperspotifycomwebapigetrelatedartists
      x-api-path-slug: artistsidrelatedartists-get
      parameters:
      - in: path
        name: id
        description: The Spotify ID for the artist
      responses:
        200:
          description: OK
      tags:
      - Music
      - Artists
  /artists/{id}/top-tracks:
    get:
      summary: Get Artist Top Tracks
      description: '[Get an Artist''s Top Tracks](https://developer.spotify.com/web-api/get-artists-top-tracks/)'
      operationId: get-an-artists-top-trackshttpsdeveloperspotifycomwebapigetartiststoptracks
      x-api-path-slug: artistsidtoptracks-get
      parameters:
      - in: query
        name: country
        description: The country (an ISO 3166-1 alpha-2 country code)
      - in: path
        name: id
        description: The Spotify ID for the artist
      responses:
        200:
          description: OK
      tags:
      - Music
      - Artists
      - Tracks
  /browse/categories:
    get:
      summary: Browse Categories
      description: '[Get a List of Browse Categories](https://developer.spotify.com/web-api/get-list-categories/)'
      operationId: get-a-list-of-browse-categorieshttpsdeveloperspotifycomwebapigetlistcategories
      x-api-path-slug: browsecategories-get
      parameters:
      - in: header
        name: Accept
        description: It is used to set specified media type
      - in: query
        name: country
        description: The country (an ISO 3166-1 alpha-2 country code)
      - in: query
        name: limit
        description: The maximum number of items to return
      - in: query
        name: locale
        description: The desired language, consisting of an ISO 639 language code
          and an ISO 3166-1 alpha-2 country code, joined by an underscore
      - in: query
        name: offset
        description: The index of the first item to return
      responses:
        200:
          description: OK
      tags:
      - Music
      - Categories
  /browse/categories/{category_id}:
    get:
      summary: Browse Category
      description: '[Get a Single Browse Category](https://developer.spotify.com/web-api/get-category/)'
      operationId: get-a-single-browse-categoryhttpsdeveloperspotifycomwebapigetcategory
      x-api-path-slug: browsecategoriescategory-id-get
      parameters:
      - in: header
        name: Accept
        description: It is used to set specified media type
      - in: path
        name: category_id
        description: The Spotify ID of the category you wish to fetch
      - in: query
        name: country
        description: The country (an ISO 3166-1 alpha-2 country code)
      - in: query
        name: locale
        description: The desired language, consisting of an ISO 639 language code
          and an ISO 3166-1 alpha-2 country code, joined by an underscore
      responses:
        200:
          description: OK
      tags:
      - Music
      - Categories
      - Playlists
  /browse/categories/{category_id}/playlists:
    get:
      summary: Browse Category Playlists
      description: '[Get a Category''s playlists](https://developer.spotify.com/web-api/get-categorys-playlists/)'
      operationId: get-a-categorys-playlistshttpsdeveloperspotifycomwebapigetcategorysplaylists
      x-api-path-slug: browsecategoriescategory-idplaylists-get
      parameters:
      - in: header
        name: Accept
        description: It is used to set specified media type
      - in: path
        name: category_id
        description: The Spotify ID of the category you wish to fetch
      - in: query
        name: country
        description: The country (an ISO 3166-1 alpha-2 country code)
      - in: query
        name: limit
        description: The maximum number of items to return
      - in: query
        name: offset
        description: The index of the first item to return
      responses:
        200:
          description: OK
      tags:
      - Music
      - Playlists
  /browse/featured-playlists:
    get:
      summary: Browse Featured Playlists
      description: '[Get a List of Featured Playlists](https://developer.spotify.com/web-api/get-list-featured-playlists/)'
      operationId: get-a-list-of-featured-playlistshttpsdeveloperspotifycomwebapigetlistfeaturedplaylists
      x-api-path-slug: browsefeaturedplaylists-get
      parameters:
      - in: header
        name: Accept
        description: It is used to set specified media type
      - in: query
        name: country
        description: The country (an ISO 3166-1 alpha-2 country code)
      - in: query
        name: limit
        description: The maximum number of items to return
      - in: query
        name: locale
        description: The desired language, consisting of an ISO 639 language code
          and an ISO 3166-1 alpha-2 country code, joined by an underscore
      - in: query
        name: offset
        description: The index of the first item to return
      - in: query
        name: timestamp
        description: A timestamp in ISO 8601 format (yyyy-MM-ddTHH:mm:ss) with the
          users local time to get results tailored to a specific date and time in
          the day
      responses:
        200:
          description: OK
      tags:
      - Music
      - Playlists
  /browse/new-releases:
    get:
      summary: Browse New Releases
      description: '[Get a List of New Releases](https://developer.spotify.com/web-api/get-list-new-releases/)'
      operationId: get-a-list-of-new-releaseshttpsdeveloperspotifycomwebapigetlistnewreleases
      x-api-path-slug: browsenewreleases-get
      parameters:
      - in: header
        name: Accept
        description: It is used to set specified media type
      - in: query
        name: country
        description: The country (an ISO 3166-1 alpha-2 country code)
      - in: query
        name: limit
        description: The maximum number of items to return
      - in: query
        name: offset
        description: The index of the first item to return
      responses:
        200:
          description: OK
      tags:
      - Music
      - New Releases
  /me:
    get:
      summary: Get Me
      description: '[Get Current User''s Profile](https://developer.spotify.com/web-api/get-current-users-profile/)'
      operationId: get-current-users-profilehttpsdeveloperspotifycomwebapigetcurrentusersprofile
      x-api-path-slug: me-get
      responses:
        200:
          description: OK
      tags:
      - Music
      - Me
  /me/following:
    delete:
      summary: Delete Following
      description: '[Unfollow Artists or Users](https://developer.spotify.com/web-api/unfollow-artists-users/)'
      operationId: unfollow-artists-or-usershttpsdeveloperspotifycomwebapiunfollowartistsusers
      x-api-path-slug: mefollowing-delete
      parameters:
      - in: query
        name: ids
        description: A comma-separated list of the artists or users ids
      - in: query
        name: type
        description: The type to unfollow
      responses:
        200:
          description: OK
      tags:
      - Music
      - Me
      - Following
    get:
      summary: Get Following
      description: '[Get User''s Followed Artists](https://developer.spotify.com/web-api/get-followed-artists/)'
      operationId: get-users-followed-artistshttpsdeveloperspotifycomwebapigetfollowedartists
      x-api-path-slug: mefollowing-get
      parameters:
      - in: query
        name: after
        description: The last artist ID retrieved from the previous request
      - in: query
        name: limit
        description: The maximum number of items to return
      - in: query
        name: type
        description: The ID type, currently only artist is supported
      responses:
        200:
          description: OK
      tags:
      - Music
      - Me
      - Following
    put:
      summary: Update Following
      description: '[Follow Artists or Users](https://developer.spotify.com/web-api/follow-artists-users/)'
      operationId: follow-artists-or-usershttpsdeveloperspotifycomwebapifollowartistsusers
      x-api-path-slug: mefollowing-put
      parameters:
      - in: query
        name: ids
        description: A comma-separated list of the artists or users ids
      - in: query
        name: type
        description: The type to follow
      responses:
        200:
          description: OK
      tags:
      - Music
      - Me
      - Following
  /me/following/contains:
    get:
      summary: Get Following contains
      description: '[Check if Current User Follows Artists or Users](https://developer.spotify.com/web-api/check-current-user-follows/)'
      operationId: check-if-current-user-follows-artists-or-usershttpsdeveloperspotifycomwebapicheckcurrentuserfollows
      x-api-path-slug: mefollowingcontains-get
      parameters:
      - in: query
        name: ids
        description: A comma-separated string of the artists or users ids
      - in: query
        name: type
        description: The type to follow
      responses:
        200:
          description: OK
      tags:
      - Music
      - Me
      - Following
  /me/tracks:
    delete:
      summary: Delete My Tracks
      description: '[Remove Tracks for Current User](https://developer.spotify.com/web-api/remove-tracks-user/)'
      operationId: remove-tracks-for-current-userhttpsdeveloperspotifycomwebapiremovetracksuser
      x-api-path-slug: metracks-delete
      parameters:
      - in: header
        name: Accept
        description: It is used to set specified media type
      - in: query
        name: ids
        description: A comma-separated list of IDs
      responses:
        200:
          description: OK
      tags:
      - Music
      - Me
      - Tracks
    get:
      summary: Get My Tracks
      description: '[Get Current User''s Saved Tracks](https://developer.spotify.com/web-api/get-users-saved-tracks/)'
      operationId: get-current-users-saved-trackshttpsdeveloperspotifycomwebapigetuserssavedtracks
      x-api-path-slug: metracks-get
      parameters:
      - in: header
        name: Accept
        description: It is used to set specified media type
      - in: query
        name: limit
        description: The maximum number of items to return
      - in: query
        name: market
        description: The market (an ISO 3166-1 alpha-2 country code)
      - in: query
        name: offset
        description: The index of the first item to return
      responses:
        200:
          description: OK
      tags:
      - Music
      - Me
      - Tracks
    put:
      summary: Update My Tracks
      description: '[Save Tracks for Current User](https://developer.spotify.com/web-api/save-tracks-user/)'
      operationId: save-tracks-for-current-userhttpsdeveloperspotifycomwebapisavetracksuser
      x-api-path-slug: metracks-put
      parameters:
      - in: header
        name: Accept
        description: It is used to set specified media type
      - in: query
        name: ids
        description: A comma-separated list of IDs
      responses:
        200:
          description: OK
      tags:
      - Music
      - Me
      - Tracks
  /me/tracks/contains:
    get:
      summary: Get My Track Contains
      description: '[Check Current User''s Saved Tracks](https://developer.spotify.com/web-api/check-users-saved-tracks/)'
      operationId: check-current-users-saved-trackshttpsdeveloperspotifycomwebapicheckuserssavedtracks
      x-api-path-slug: metrackscontains-get
      parameters:
      - in: query
        name: ids
        description: A comma-separated list of IDs
      responses:
        200:
          description: OK
      tags:
      - Music
      - Me
      - Tracks
  /search:
    get:
      summary: Search
      description: '[Search for an Item](https://developer.spotify.com/web-api/search-item/)'
      operationId: search-for-an-itemhttpsdeveloperspotifycomwebapisearchitem
      x-api-path-slug: search-get
      parameters:
      - in: query
        name: limit
        description: The maximum number of items to return
      - in: query
        name: market
        description: The market (an ISO 3166-1 alpha-2 country code)
      - in: query
        name: offset
        description: The index of the first item to return
      - in: query
        name: q
        description: The search querys keywords (and optional field filters)
      - in: query
        name: type
        description: A comma-separated list of item types to search across
      responses:
        200:
          description: OK
      tags:
      - Music
      - Search
x-streamrank:
  polling_total_time_average: "0.1"
  polling_size_download_average: "4080.73"
  streaming_total_time_average: "0.06"
  streaming_size_download_average: "2046.76"
  change_yes: "4"
  change_no: "195"
  time_percentage: "45"
  size_percentage: "50"
  change_percentage: "2"
  last_run: "2018-05-06"
  days_run: "1"
  minute_run: "0"
---