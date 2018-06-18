{
  "info": {
    "name": "Azure Scheduler API Job Collections Disable",
    "_postman_id": "f527b201-a223-4591-b1f4-3f71bbd84286",
    "description": "Disables all of the jobs in the job collection.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "job collections",
      "item": [
        {
          "id": "9036c6e6-52ba-4cde-b651-27668f6e51cd",
          "name": "JobCollections_Disable",
          "request": {
            "url": {
              "protocol": "http",
              "host": "management.azure.com",
              "path": [
                "subscriptions/:subscriptionId/resourceGroups/:resourceGroupName/providers/Microsoft.Scheduler/jobCollections/:jobCollectionName/disable"
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
            "description": "Disables all of the jobs in the job collection"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e4c9add6-5414-44bb-aab9-3a19e9f23be3"
            }
          ]
        }
      ]
    }
  ]
}