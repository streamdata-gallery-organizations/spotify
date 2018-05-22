---
name: Spotify
x-slug: spotify
description: Spotify has created a lightweight software application that allows instant
  listening to specific tracks or albums with virtually no buffering delay. It was
  launched in the fall of 2008 and had approximately 10 million users by September
  2010. Spotify offers streaming music from major and independent record labels including
  Sony, EMI, Warner Music Group, and Universal. Users download Spotify and then log
  onto their service enabling the on-demand streaming of music. Music can be browsed
  by artist, album, record label, genre or playlist as well as by direct searches.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/spotify-green-logo.jpg
x-kinRank: "8"
x-alexaRank: ""
tags: Spotify
created: "2018-05-22"
modified: "2018-05-22"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spotify/master/_listings/spotify/apis.md
specificationVersion: "0.14"
apis:
- name: Spotify Get Albums
  x-api-slug: spotify
  description: '[Get Several Albums](https://developer.spotify.com/web-api/get-several-albums/)'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/spotify-green-logo.jpg
  humanURL: http://www.spotify.com
  baseURL: https://api.spotify.com//v1//albums
  tags: Music,Albums
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spotify/master/_listings/spotify/albums-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spotify/master/_listings/spotify/albums-get-openapi.md
- name: Spotify Get Album
  x-api-slug: spotify
  description: '[Get an Album](https://developer.spotify.com/web-api/get-album/)'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/spotify-green-logo.jpg
  humanURL: http://www.spotify.com
  baseURL: https://api.spotify.com//v1//albums/{id}
  tags: Music,Albums
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spotify/master/_listings/spotify/albumsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spotify/master/_listings/spotify/albumsid-get-openapi.md
- name: Spotify Get Album Tracks
  x-api-slug: spotify
  description: '[Get an Album''s Tracks](https://developer.spotify.com/web-api/get-albums-tracks/)'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/spotify-green-logo.jpg
  humanURL: http://www.spotify.com
  baseURL: https://api.spotify.com//v1//albums/{id}/tracks
  tags: Music,Album,Tracks
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spotify/master/_listings/spotify/albumsidtracks-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spotify/master/_listings/spotify/albumsidtracks-get-openapi.md
- name: Spotify Get Artists
  x-api-slug: spotify
  description: '[Get Several Artists](https://developer.spotify.com/web-api/get-several-artists/)'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/spotify-green-logo.jpg
  humanURL: http://www.spotify.com
  baseURL: https://api.spotify.com//v1//artists
  tags: Music,Artists
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spotify/master/_listings/spotify/artists-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spotify/master/_listings/spotify/artists-get-openapi.md
- name: Spotify Get Artist
  x-api-slug: spotify
  description: '[Get an Artist](https://developer.spotify.com/web-api/get-artist/)'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/spotify-green-logo.jpg
  humanURL: http://www.spotify.com
  baseURL: https://api.spotify.com//v1//artists/{id}
  tags: Music,Artists
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spotify/master/_listings/spotify/artistsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spotify/master/_listings/spotify/artistsid-get-openapi.md
- name: Spotify Get Artist Albums
  x-api-slug: spotify
  description: '[Get an Artist''s Albums](https://developer.spotify.com/web-api/get-artists-albums/)'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/spotify-green-logo.jpg
  humanURL: http://www.spotify.com
  baseURL: https://api.spotify.com//v1//artists/{id}/albums
  tags: Music,Artists,Albums
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spotify/master/_listings/spotify/artistsidalbums-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spotify/master/_listings/spotify/artistsidalbums-get-openapi.md
- name: Spotify Get Artist Related ARtists
  x-api-slug: spotify
  description: '[Get an Artist''s Related Artists](https://developer.spotify.com/web-api/get-related-artists/)'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/spotify-green-logo.jpg
  humanURL: http://www.spotify.com
  baseURL: https://api.spotify.com//v1//artists/{id}/related-artists
  tags: Music,Artists
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spotify/master/_listings/spotify/artistsidrelatedartists-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spotify/master/_listings/spotify/artistsidrelatedartists-get-openapi.md
- name: Spotify Get Artist Top Tracks
  x-api-slug: spotify
  description: '[Get an Artist''s Top Tracks](https://developer.spotify.com/web-api/get-artists-top-tracks/)'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/spotify-green-logo.jpg
  humanURL: http://www.spotify.com
  baseURL: https://api.spotify.com//v1//artists/{id}/top-tracks
  tags: Music,Artists,Tracks
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spotify/master/_listings/spotify/artistsidtoptracks-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spotify/master/_listings/spotify/artistsidtoptracks-get-openapi.md
- name: Spotify Browse Categories
  x-api-slug: spotify
  description: '[Get a List of Browse Categories](https://developer.spotify.com/web-api/get-list-categories/)'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/spotify-green-logo.jpg
  humanURL: http://www.spotify.com
  baseURL: https://api.spotify.com//v1//browse/categories
  tags: Music,Categories
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spotify/master/_listings/spotify/browsecategories-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spotify/master/_listings/spotify/browsecategories-get-openapi.md
- name: Spotify Browse Category
  x-api-slug: spotify
  description: '[Get a Single Browse Category](https://developer.spotify.com/web-api/get-category/)'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/spotify-green-logo.jpg
  humanURL: http://www.spotify.com
  baseURL: https://api.spotify.com//v1//browse/categories/{category_id}
  tags: Music,Categories,Playlists
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spotify/master/_listings/spotify/browsecategoriescategory-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spotify/master/_listings/spotify/browsecategoriescategory-id-get-openapi.md
- name: Spotify Browse Category Playlists
  x-api-slug: spotify
  description: '[Get a Category''s playlists](https://developer.spotify.com/web-api/get-categorys-playlists/)'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/spotify-green-logo.jpg
  humanURL: http://www.spotify.com
  baseURL: https://api.spotify.com//v1//browse/categories/{category_id}/playlists
  tags: Music,Playlists
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spotify/master/_listings/spotify/browsecategoriescategory-idplaylists-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spotify/master/_listings/spotify/browsecategoriescategory-idplaylists-get-openapi.md
- name: Spotify Browse Featured Playlists
  x-api-slug: spotify
  description: '[Get a List of Featured Playlists](https://developer.spotify.com/web-api/get-list-featured-playlists/)'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/spotify-green-logo.jpg
  humanURL: http://www.spotify.com
  baseURL: https://api.spotify.com//v1//browse/featured-playlists
  tags: Music,Playlists
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spotify/master/_listings/spotify/browsefeaturedplaylists-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spotify/master/_listings/spotify/browsefeaturedplaylists-get-openapi.md
- name: Spotify Browse New Releases
  x-api-slug: spotify
  description: '[Get a List of New Releases](https://developer.spotify.com/web-api/get-list-new-releases/)'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/spotify-green-logo.jpg
  humanURL: http://www.spotify.com
  baseURL: https://api.spotify.com//v1//browse/new-releases
  tags: Music,New Releases
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spotify/master/_listings/spotify/browsenewreleases-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spotify/master/_listings/spotify/browsenewreleases-get-openapi.md
- name: Spotify Get Me
  x-api-slug: spotify
  description: '[Get Current User''s Profile](https://developer.spotify.com/web-api/get-current-users-profile/)'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/spotify-green-logo.jpg
  humanURL: http://www.spotify.com
  baseURL: https://api.spotify.com//v1//me
  tags: Music,Me
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spotify/master/_listings/spotify/me-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spotify/master/_listings/spotify/me-get-openapi.md
- name: Spotify Delete Following
  x-api-slug: spotify
  description: '[Unfollow Artists or Users](https://developer.spotify.com/web-api/unfollow-artists-users/)'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/spotify-green-logo.jpg
  humanURL: http://www.spotify.com
  baseURL: https://api.spotify.com//v1//me/following
  tags: Music,Me,Following
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spotify/master/_listings/spotify/mefollowing-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spotify/master/_listings/spotify/mefollowing-delete-openapi.md
- name: Spotify Get Following
  x-api-slug: spotify
  description: '[Get User''s Followed Artists](https://developer.spotify.com/web-api/get-followed-artists/)'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/spotify-green-logo.jpg
  humanURL: http://www.spotify.com
  baseURL: https://api.spotify.com//v1//me/following
  tags: Music,Me,Following
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spotify/master/_listings/spotify/mefollowing-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spotify/master/_listings/spotify/mefollowing-get-openapi.md
- name: Spotify Update Following
  x-api-slug: spotify
  description: '[Follow Artists or Users](https://developer.spotify.com/web-api/follow-artists-users/)'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/spotify-green-logo.jpg
  humanURL: http://www.spotify.com
  baseURL: https://api.spotify.com//v1//me/following
  tags: Music,Me,Following
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spotify/master/_listings/spotify/mefollowing-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spotify/master/_listings/spotify/mefollowing-put-openapi.md
- name: Spotify Get Following contains
  x-api-slug: spotify
  description: '[Check if Current User Follows Artists or Users](https://developer.spotify.com/web-api/check-current-user-follows/)'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/spotify-green-logo.jpg
  humanURL: http://www.spotify.com
  baseURL: https://api.spotify.com//v1//me/following/contains
  tags: Music,Me,Following
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spotify/master/_listings/spotify/mefollowingcontains-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spotify/master/_listings/spotify/mefollowingcontains-get-openapi.md
- name: Spotify Delete My Tracks
  x-api-slug: spotify
  description: '[Remove Tracks for Current User](https://developer.spotify.com/web-api/remove-tracks-user/)'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/spotify-green-logo.jpg
  humanURL: http://www.spotify.com
  baseURL: https://api.spotify.com//v1//me/tracks
  tags: Music,Me,Tracks
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spotify/master/_listings/spotify/metracks-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spotify/master/_listings/spotify/metracks-delete-openapi.md
- name: Spotify Get My Tracks
  x-api-slug: spotify
  description: '[Get Current User''s Saved Tracks](https://developer.spotify.com/web-api/get-users-saved-tracks/)'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/spotify-green-logo.jpg
  humanURL: http://www.spotify.com
  baseURL: https://api.spotify.com//v1//me/tracks
  tags: Music,Me,Tracks
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spotify/master/_listings/spotify/metracks-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spotify/master/_listings/spotify/metracks-get-openapi.md
- name: Spotify Update My Tracks
  x-api-slug: spotify
  description: '[Save Tracks for Current User](https://developer.spotify.com/web-api/save-tracks-user/)'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/spotify-green-logo.jpg
  humanURL: http://www.spotify.com
  baseURL: https://api.spotify.com//v1//me/tracks
  tags: Music,Me,Tracks
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spotify/master/_listings/spotify/metracks-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spotify/master/_listings/spotify/metracks-put-openapi.md
- name: Spotify Get My Track Contains
  x-api-slug: spotify
  description: '[Check Current User''s Saved Tracks](https://developer.spotify.com/web-api/check-users-saved-tracks/)'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/spotify-green-logo.jpg
  humanURL: http://www.spotify.com
  baseURL: https://api.spotify.com//v1//me/tracks/contains
  tags: Music,Me,Tracks
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spotify/master/_listings/spotify/metrackscontains-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spotify/master/_listings/spotify/metrackscontains-get-openapi.md
- name: Spotify Search
  x-api-slug: spotify
  description: '[Search for an Item](https://developer.spotify.com/web-api/search-item/)'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/spotify-green-logo.jpg
  humanURL: http://www.spotify.com
  baseURL: https://api.spotify.com//v1//search
  tags: Music,Search
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spotify/master/_listings/spotify/search-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spotify/master/_listings/spotify/search-get-openapi.md
- name: Spotify Get Tracks
  x-api-slug: spotify
  description: '[Get Several Tracks](https://developer.spotify.com/web-api/get-several-tracks/)'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/spotify-green-logo.jpg
  humanURL: http://www.spotify.com
  baseURL: https://api.spotify.com//v1//tracks
  tags: Music,Tracks
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spotify/master/_listings/spotify/tracks-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spotify/master/_listings/spotify/tracks-get-openapi.md
- name: Spotify Get Track
  x-api-slug: spotify
  description: '[Get a Track](https://developer.spotify.com/web-api/get-track/)'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/spotify-green-logo.jpg
  humanURL: http://www.spotify.com
  baseURL: https://api.spotify.com//v1//tracks/{id}
  tags: Music,Tracks
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spotify/master/_listings/spotify/tracksid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spotify/master/_listings/spotify/tracksid-get-openapi.md
- name: Spotify Get User
  x-api-slug: spotify
  description: '[Get a User''s Profile](https://developer.spotify.com/web-api/get-users-profile/)'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/spotify-green-logo.jpg
  humanURL: http://www.spotify.com
  baseURL: https://api.spotify.com//v1//users/{user_id}
  tags: Music,User
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spotify/master/_listings/spotify/usersuser-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spotify/master/_listings/spotify/usersuser-id-get-openapi.md
- name: Spotify Get User Playlists
  x-api-slug: spotify
  description: '[Get a List of a User''s Playlists](https://developer.spotify.com/web-api/get-list-users-playlists/)'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/spotify-green-logo.jpg
  humanURL: http://www.spotify.com
  baseURL: https://api.spotify.com//v1//users/{user_id}/playlists
  tags: Music,User,Playlists
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spotify/master/_listings/spotify/usersuser-idplaylists-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spotify/master/_listings/spotify/usersuser-idplaylists-get-openapi.md
- name: Spotify Add User Playlists
  x-api-slug: spotify
  description: '[Create a Playlist](https://developer.spotify.com/web-api/create-playlist/)'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/spotify-green-logo.jpg
  humanURL: http://www.spotify.com
  baseURL: https://api.spotify.com//v1//users/{user_id}/playlists
  tags: Music,User,Playlists
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spotify/master/_listings/spotify/usersuser-idplaylists-post-openapi.md
- name: Spotify Get User Playlist
  x-api-slug: spotify
  description: '[Get a Playlist](https://developer.spotify.com/web-api/get-playlist/)'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/spotify-green-logo.jpg
  humanURL: http://www.spotify.com
  baseURL: https://api.spotify.com//v1//users/{user_id}/playlists/{playlist_id}
  tags: Music,User,Playlists
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spotify/master/_listings/spotify/usersuser-idplaylistsplaylist-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spotify/master/_listings/spotify/usersuser-idplaylistsplaylist-id-get-openapi.md
- name: Spotify Update User Playlist
  x-api-slug: spotify
  description: '[Change a Playlist''s Details](https://developer.spotify.com/web-api/change-playlist-details/)'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/spotify-green-logo.jpg
  humanURL: http://www.spotify.com
  baseURL: https://api.spotify.com//v1//users/{user_id}/playlists/{playlist_id}
  tags: Music,User,Playlists
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spotify/master/_listings/spotify/usersuser-idplaylistsplaylist-id-put-openapi.md
- name: Spotify Delete User Playlist Followers
  x-api-slug: spotify
  description: '[Unfollow a Playlist](https://developer.spotify.com/web-api/unfollow-playlist/)'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/spotify-green-logo.jpg
  humanURL: http://www.spotify.com
  baseURL: https://api.spotify.com//v1//users/{user_id}/playlists/{playlist_id}/followers
  tags: Music,User,Playlists,Followers
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spotify/master/_listings/spotify/usersuser-idplaylistsplaylist-idfollowers-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spotify/master/_listings/spotify/usersuser-idplaylistsplaylist-idfollowers-delete-openapi.md
- name: Spotify Update User Playlist Followers
  x-api-slug: spotify
  description: '[Follow a Playlist](https://developer.spotify.com/web-api/follow-playlist/)'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/spotify-green-logo.jpg
  humanURL: http://www.spotify.com
  baseURL: https://api.spotify.com//v1//users/{user_id}/playlists/{playlist_id}/followers
  tags: Music,User,Playlists,Followers
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spotify/master/_listings/spotify/usersuser-idplaylistsplaylist-idfollowers-put-openapi.md
- name: Spotify Get User Playlist Followers Contains
  x-api-slug: spotify
  description: '[Check if Users Follow a Playlist](https://developer.spotify.com/web-api/check-user-following-playlist/)'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/spotify-green-logo.jpg
  humanURL: http://www.spotify.com
  baseURL: https://api.spotify.com//v1//users/{user_id}/playlists/{playlist_id}/followers/contains
  tags: Music,User,Playlists,Followers
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spotify/master/_listings/spotify/usersuser-idplaylistsplaylist-idfollowerscontains-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spotify/master/_listings/spotify/usersuser-idplaylistsplaylist-idfollowerscontains-get-openapi.md
- name: Spotify Delete User Playlist Tracks
  x-api-slug: spotify
  description: '[Remove Tracks from a Playlist](https://developer.spotify.com/web-api/remove-tracks-playlist/)'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/spotify-green-logo.jpg
  humanURL: http://www.spotify.com
  baseURL: https://api.spotify.com//v1//users/{user_id}/playlists/{playlist_id}/tracks
  tags: Music,User,Playlists,Tracks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spotify/master/_listings/spotify/usersuser-idplaylistsplaylist-idtracks-delete-openapi.md
- name: Spotify Get User Playlist Tracks
  x-api-slug: spotify
  description: '[Get a Playlist''s Tracks](https://developer.spotify.com/web-api/get-playlists-tracks/)'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/spotify-green-logo.jpg
  humanURL: http://www.spotify.com
  baseURL: https://api.spotify.com//v1//users/{user_id}/playlists/{playlist_id}/tracks
  tags: Music,User,Playlists,Tracks
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spotify/master/_listings/spotify/usersuser-idplaylistsplaylist-idtracks-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spotify/master/_listings/spotify/usersuser-idplaylistsplaylist-idtracks-get-openapi.md
- name: Spotify Add User Playlist Track
  x-api-slug: spotify
  description: '[Add Tracks to a Playlist](https://developer.spotify.com/web-api/add-tracks-to-playlist/)'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/spotify-green-logo.jpg
  humanURL: http://www.spotify.com
  baseURL: https://api.spotify.com//v1//users/{user_id}/playlists/{playlist_id}/tracks
  tags: Music,User,Playlists,Tracks
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spotify/master/_listings/spotify/usersuser-idplaylistsplaylist-idtracks-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spotify/master/_listings/spotify/usersuser-idplaylistsplaylist-idtracks-post-openapi.md
- name: Spotify Update User Playlist Track
  x-api-slug: spotify
  description: '[Reorder or replace a Playlist''s Tracks](https://developer.spotify.com/web-api/reorder-playlists-tracks/)'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/spotify-green-logo.jpg
  humanURL: http://www.spotify.com
  baseURL: https://api.spotify.com//v1//users/{user_id}/playlists/{playlist_id}/tracks
  tags: Music,User,Playlists,Tracks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spotify/master/_listings/spotify/usersuser-idplaylistsplaylist-idtracks-put-openapi.md
- name: Spotify
  x-api-slug: spotify
  description: Spotify has created a lightweight software application that allows
    instant listening to specific tracks or albums with virtually no buffering delay.
    It was launched in the fall of 2008 and had approximately 10 million users by
    September 2010. Spotify offers streaming music from major and independent record
    labels including Sony, EMI, Warner Music Group, and Universal. Users download
    Spotify and then log onto their service enabling the on-demand streaming of music.
    Music can be browsed by artist, album, record label, genre or playlist as well
    as by direct searches.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/spotify-green-logo.jpg
  humanURL: http://www.spotify.com
  baseURL: https://api.spotify.com//v1
  tags: Spotify
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/spotify/master/_listings/spotify/openapi.md
x-common:
- type: x-apijson--authoritative
  url: https://developer.spotify.com/wp-content/uploads/apis.json
- type: x-android-sdk
  url: https://developer.spotify.com/technologies/spotify-android-sdk/
- type: x-application-gallery
  url: https://developer.spotify.com/my-applications/
- type: x-application-gallery
  url: https://developer.spotify.com/showcase/
- type: x-base-url
  url: https://api.spotify.com
- type: x-blog
  url: http://www.spotify.com/blog/
- type: x-blog-rss
  url: http://www.spotify.com/blog/feed
- type: x-change-log
  url: https://developer.spotify.com/web-api/change-log/
- type: x-console
  url: https://developer.spotify.com/web-api/console/
- type: x-crunchbase
  url: http://www.crunchbase.com/company/spotify
- type: x-developer
  url: https://developer.spotify.com/
- type: x-ios-sdk
  url: https://developer.spotify.com/technologies/spotify-ios-sdk/
- type: x-issues
  url: https://github.com/spotify/web-api/issues
- type: x-stack-overflow
  url: http://stackoverflow.com/questions/tagged/spotify
- type: x-terms-of-service
  url: https://developer.spotify.com/developer-terms-of-use/
- type: x-twitter
  url: https://twitter.com/SpotifyPlatform
- type: x-twitter
  url: https://twitter.com/spotify
- type: x-github
  url: https://github.com/spotify
- type: x-website
  url: http://www.spotify.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---