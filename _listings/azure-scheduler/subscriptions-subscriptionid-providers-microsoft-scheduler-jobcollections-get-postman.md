{
  "info": {
    "name": "Azure Scheduler API Job Collections List By Subscription",
    "_postman_id": "e1d021f5-bf15-47ad-aada-d410e1977297",
    "description": "Gets all job collections under specified subscription.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "job collections subscription",
      "item": [
        {
          "id": "dc66399c-3a2e-4bd0-b606-9e20e400f72b",
          "name": "JobCollections_ListBySubscription",
          "request": {
            "url": {
              "protocol": "http",
              "host": "management.azure.com",
              "path": [
                "subscriptions/:subscriptionId/providers/Microsoft.Scheduler/jobCollections"
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
            "description": "Gets all job collections under specified subscription"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9faf2589-55fa-4a26-9f7e-95b7faba9548"
            }
          ]
        }
      ]
    }
  ]
}