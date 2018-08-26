{
  "info": {
    "name": "Shopify Get a count of all collections",
    "_postman_id": "85224d39-c7b8-4248-8fa8-a2f1fa6994b0",
    "description": "Get a count of all collections.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Commerce",
      "item": [
        {
          "id": "58767756-4f60-4123-9acd-b95f02f34ff4",
          "name": "getAdminCustomCollections.json",
          "request": {
            "url": "http://DefaultParameterValue:DefaultParameterValue@DefaultParameterValue.myshopify.com/admin/custom_collections.json",
            "method": "GET",
            "header": [
              {
                "key": "Content-Type",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get a list of all custom collections."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f4ccf49c-9f1b-41f5-b97b-8e0182d4bb82"
            }
          ]
        },
        {
          "id": "76c44797-21fe-4685-bda8-e4cf2100d69c",
          "name": "getAdminCustomCollections246409795.json",
          "request": {
            "url": "http://DefaultParameterValue:DefaultParameterValue@DefaultParameterValue.myshopify.com/admin/custom_collections/246409795.json",
            "method": "GET",
            "header": [
              {
                "key": "Content-Type",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get a single custom collections."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2d375e23-034e-4afb-88f6-64bba6def10b"
            }
          ]
        },
        {
          "id": "d1b62404-79d0-47db-9fd0-ac1b57fe1e4b",
          "name": "getAdminSmartCollectionsCount.json",
          "request": {
            "url": "http://DefaultParameterValue:DefaultParameterValue@DefaultParameterValue.myshopify.com/admin/smart_collections/count.json",
            "method": "GET",
            "header": [
              {
                "key": "Content-Type",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get a count of all collections."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7f5cdeae-25a1-4eb7-b381-239872917c96"
            }
          ]
        }
      ]
    }
  ]
}