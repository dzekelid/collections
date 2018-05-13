{
  "info": {
    "name": "Azure Scheduler API Job Collections Enable",
    "_postman_id": "b2a66864-ebb5-4809-82d4-c97a54b86b29",
    "description": "Enables all of the jobs in the job collection.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "job collections",
      "item": [
        {
          "id": "fb237a90-27d0-4152-af86-678a02a85bf4",
          "name": "JobCollections_Enable",
          "request": {
            "url": {
              "protocol": "http",
              "host": "management.azure.com",
              "path": [
                "subscriptions/:subscriptionId/resourceGroups/:resourceGroupName/providers/Microsoft.Scheduler/jobCollections/:jobCollectionName/enable"
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
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Enables all of the jobs in the job collection"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a29e2eba-e335-42e4-be3b-bd6027c699fa"
            }
          ]
        }
      ]
    }
  ]
}