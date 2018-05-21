{
  "info": {
    "name": "Azure Scheduler API Job Collections List By Resource Group",
    "_postman_id": "fc1b4168-8ecc-42af-8063-d9fb66645dc1",
    "description": "Gets all job collections under specified resource group.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "job collections resource group",
      "item": [
        {
          "id": "3d492507-4a93-4c00-bfd8-39cd0a1f7ba0",
          "name": "JobCollections_ListByResourceGroup",
          "request": {
            "url": {
              "protocol": "http",
              "host": "management.azure.com",
              "path": [
                "subscriptions/:subscriptionId/resourceGroups/:resourceGroupName/providers/Microsoft.Scheduler/jobCollections"
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
            "description": "Gets all job collections under specified resource group"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "59aa4e57-8043-4200-811f-20d12bc67469"
            }
          ]
        }
      ]
    }
  ]
}