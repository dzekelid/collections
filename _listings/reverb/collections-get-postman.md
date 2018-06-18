{
  "info": {
    "name": "reverb Get Collections",
    "_postman_id": "bac56746-b72f-4d0b-8d77-8e1fc033ebf8",
    "description": "List of curated collections",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "My",
      "item": [
        {
          "id": "9ca38f04-6865-4d14-97b2-9e0108bccdc3",
          "name": "getMyFollowsCollectionsSlug",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.reverb.com",
              "path": [
                "api",
                "my/follows/collections/:slug"
              ],
              "variable": [
                {
                  "id": "slug",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get my follows collections slug."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b6fc20db-6c81-490b-b34e-814ac4ccf967"
            }
          ]
        },
        {
          "id": "a0aabfb9-f53b-45e0-a770-cbd1942125ca",
          "name": "postMyFollowsCollectionsSlug",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.reverb.com",
              "path": [
                "api",
                "my/follows/collections/:slug"
              ],
              "variable": [
                {
                  "id": "slug",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Post my follows collections slug."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5706a564-3d0c-41cf-942e-81d6765a7704"
            }
          ]
        },
        {
          "id": "b7bee546-8fd2-432c-8cd0-09aacce15750",
          "name": "deleteMyFollowsCollectionsSlug",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.reverb.com",
              "path": [
                "api",
                "my/follows/collections/:slug"
              ],
              "variable": [
                {
                  "id": "slug",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Delete my follows collections slug."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "04b026f5-9ef2-46a7-9deb-683fd0d2b4f8"
            }
          ]
        }
      ]
    },
    {
      "name": "Collections",
      "item": [
        {
          "id": "5badfdbb-d078-4ebc-b6ad-90637cb9ae5b",
          "name": "getCollections",
          "request": {
            "url": "http://api.reverb.com/api/collections",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List of curated collections"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1d403e93-e236-4420-8c62-aaa149b1b38a"
            }
          ]
        }
      ]
    }
  ]
}