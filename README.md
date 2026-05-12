# Spotify API Explorer 🎵

A Postman collection exploring Spotify's Web API with OAuth 2.0 authentication.

## What This Does
- Fetches artist details by ID
- Retrieves top tracks for an artist
- Authenticated using OAuth 2.0 Client Credentials Flow

## API Concepts Covered
- OAuth 2.0 Bearer Token authentication
- GET requests with query parameters
- JSON response parsing
- Postman environment variables

## How to Use
1. Import the .json file into Postman
2. Create a Spotify Developer account at developer.spotify.com
3. Add your Client ID and Client Secret as Postman environment variables
4. Run the requests!
Sample response
{
    "artists": {
        "href": "https://api.spotify.com/v1/search?offset=0&limit=5&query=Taylor%20Swift&type=artist",
        "limit": 5,
        "next": "https://api.spotify.com/v1/search?offset=5&limit=5&query=Taylor%20Swift&type=artist",
        "offset": 0,
        "previous": null,
        "total": 9,
        "items": [
            {
                "external_urls": {
                    "spotify": "https://open.spotify.com/artist/06HL4z0CvFAxyc27GXpf02"
                },
                "href": "https://api.spotify.com/v1/artists/06HL4z0CvFAxyc27GXpf02",
                "id": "06HL4z0CvFAxyc27GXpf02",
                "images": [
                    {
                        "url": "https://i.scdn.co/image/ab6761610000e5ebe2e8e7ff002a4afda1c7147e",
                        "height": 640,
                        "width": 640
                    },
                    {
                        "url": "https://i.scdn.co/image/ab67616100005174e2e8e7ff002a4afda1c7147e",
                        "height": 320,
                        "width": 320
                    },
                    {
                        "url": "https://i.scdn.co/image/ab6761610000f178e2e8e7ff002a4afda1c7147e",
                        "height": 160,
                        "width": 160
                    }
                ],
                "name": "Taylor Swift",
                "type": "artist",
                "uri": "spotify:artist:06HL4z0CvFAxyc27GXpf02"
            },
            {
                "external_urls": {
                    "spotify": "https://open.spotify.com/artist/6jJ0s89eD6GaHleKKya26X"
                },
                "href": "https://api.spotify.com/v1/artists/6jJ0s89eD6GaHleKKya26X",
                "id": "6jJ0s89eD6GaHleKKya26X",
                "images": [
                    {
                        "url": "https://i.scdn.co/image/ab6761610000e5eb4be5330bd48527f9dd620663",
                        "height": 640,
                        "width": 640
                    },
                    {
                        "url": "https://i.scdn.co/image/ab676161000051744be5330bd48527f9dd620663",
                        "height": 320,
                        "width": 320
                    },
                    {
                        "url": "https://i.scdn.co/image/ab6761610000f1784be5330bd48527f9dd620663",
                        "height": 160,
                        "width": 160
                    }
                ],
                "name": "Katy Perry",
                "type": "artist",
                "uri": "spotify:artist:6jJ0s89eD6GaHleKKya26X"
            },
            {
                "external_urls": {
                    "spotify": "https://open.spotify.com/artist/1Vvvx45Apu6dQqwuZQxtgW"
                },
                "href": "https://api.spotify.com/v1/artists/1Vvvx45Apu6dQqwuZQxtgW",
                "id": "1Vvvx45Apu6dQqwuZQxtgW",
                "images": [
                    {
                        "url": "https://i.scdn.co/image/ab6761610000e5ebb20a9c9cee335441838c751b",
                        "height": 640,
                        "width": 640
                    },
                    {
                        "url": "https://i.scdn.co/image/ab67616100005174b20a9c9cee335441838c751b",
                        "height": 320,
                        "width": 320
                    },
                    {
                        "url": "https://i.scdn.co/image/ab6761610000f178b20a9c9cee335441838c751b",
                        "height": 160,
                        "width": 160
                    }
                ],
                "name": "Kidz Bop Kids",
                "type": "artist",
                "uri": "spotify:artist:1Vvvx45Apu6dQqwuZQxtgW"
            },
            {
                "external_urls": {
                    "spotify": "https://open.spotify.com/artist/0DwbGCdaD8YLRiVUEiV70Q"
                },
                "href": "https://api.spotify.com/v1/artists/0DwbGCdaD8YLRiVUEiV70Q",
                "id": "0DwbGCdaD8YLRiVUEiV70Q",
                "images": [
                    {
                        "url": "https://i.scdn.co/image/ab67616d0000b2738160a48bb1693050f496b11e",
                        "height": 640,
                        "width": 640
                    },
                    {
                        "url": "https://i.scdn.co/image/ab67616d00001e028160a48bb1693050f496b11e",
                        "height": 300,
                        "width": 300
                    },
                    {
                        "url": "https://i.scdn.co/image/ab67616d000048518160a48bb1693050f496b11e",
                        "height": 64,
                        "width": 64
                    }
                ],
                "name": "Taylor Swift Piano Covers",
                "type": "artist",
                "uri": "spotify:artist:0DwbGCdaD8YLRiVUEiV70Q"
            },
            {
                "external_urls": {
                    "spotify": "https://open.spotify.com/artist/3vZoN5cnYOycsJ5KsFkjo5"
                },
                "href": "https://api.spotify.com/v1/artists/3vZoN5cnYOycsJ5KsFkjo5",
                "id": "3vZoN5cnYOycsJ5KsFkjo5",
                "images": [
                    {
                        "url": "https://i.scdn.co/image/ab67616d0000b273785702c6f41f1fa6d6c3d2b1",
                        "height": 640,
                        "width": 640
                    },
                    {
                        "url": "https://i.scdn.co/image/ab67616d00001e02785702c6f41f1fa6d6c3d2b1",
                        "height": 300,
                        "width": 300
                    },
                    {
                        "url": "https://i.scdn.co/image/ab67616d00004851785702c6f41f1fa6d6c3d2b1",
                        "height": 64,
                        "width": 64
                    }
                ],
                "name": "Taylor Swift - Evermore - Piano Covers",
                "type": "artist",
                "uri": "spotify:artist:3vZoN5cnYOycsJ5KsFkjo5"
            }
        ]
    }
}
