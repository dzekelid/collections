{
  "info": {
    "name": "Azure Scheduler API Job Collections Get",
    "_postman_id": "bf9b82ed-32ea-48b7-b2c4-c33c60c81b1a",
    "description": "Gets a job collection.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "job collections",
      "item": [
        {
          "id": "ebf7af31-bee9-4f25-9423-0501f79b7753",
          "name": "JobCollections_Get",
          "request": {
            "url": {
              "protocol": "http",
              "host": "management.azure.com",
              "path": [
                "subscriptions/:subscriptionId/resourceGroups/:resourceGroupName/providers/Microsoft.Scheduler/jobCollections/:jobCollectionName"
              ],
              "query": [
                {
                  "key": "No Name",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "jobCollectionName",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "resourceGroupName",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "subscriptionId",
                  "value": "subscriptionId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets a job collection"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "344fb34e-5f5f-454a-b932-c0f90fb5a9e2"
            }
          ]
        }
      ]
    }
  ]
}