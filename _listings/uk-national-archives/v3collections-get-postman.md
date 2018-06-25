{
  "info": {
    "name": "Getty Images Search API Get Collections",
    "_postman_id": "18a6fdfa-e245-46fb-9e91-e31ce3c095f6",
    "description": "Gets collections applicable for the customer..",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Collections",
      "item": [
        {
          "id": "6fc2c1a3-3c88-4fac-8899-113bd9cd5dfe",
          "name": "getV3Collections",
          "request": {
            "url": "http://api.gettyimages.com/v3/collections",
            "method": "GET",
            "header": [
              {
                "key": "Accept-Language",
                "value": "{}",
                "description": "Specifies the language of result values",
                "disabled": false
              },
              {
                "key": "Authorization",
                "value": "{}",
                "description": "Provide access token in the format of Bearer {token}",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Gets collections applicable for the customer.."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a86aafee-c0ba-466d-91ad-93976dc9a27d"
            }
          ]
        }
      ]
    }
  ]
}