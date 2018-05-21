---
swagger: "2.0"
x-collection-name: Azure Scheduler
x-complete: 0
info:
  title: Azure Scheduler API Job Collections Patch
  version: 1.0.0
  description: Patches an existing job collection.
host: management.azure.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /subscriptions/{subscriptionId}/providers/Microsoft.Scheduler/jobCollections:
    get:
      summary: Job Collections List By Subscription
      description: Gets all job collections under specified subscription.
      operationId: JobCollections_ListBySubscription
      x-api-path-slug: subscriptionssubscriptionidprovidersmicrosoftschedulerjobcollections-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Job Collections Subscription
  /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Scheduler/jobCollections:
    get:
      summary: Job Collections List By Resource Group
      description: Gets all job collections under specified resource group.
      operationId: JobCollections_ListByResourceGroup
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftschedulerjobcollections-get
      parameters:
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The resource group name
      responses:
        200:
          description: OK
      tags:
      - Job Collections Resource Group
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Scheduler/jobCollections/{jobCollectionName}
  : get:
      summary: Job Collections Get
      description: Gets a job collection.
      operationId: JobCollections_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftschedulerjobcollectionsjobcollectionname-get
      parameters:
      - in: path
        name: jobCollectionName
        description: The job collection name
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The resource group name
      responses:
        200:
          description: OK
      tags:
      - Job Collections
    put:
      summary: Job Collections Create Or Update
      description: Provisions a new job collection or updates an existing job collection.
      operationId: JobCollections_CreateOrUpdate
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftschedulerjobcollectionsjobcollectionname-put
      parameters:
      - in: body
        name: jobCollection
        description: The job collection definition
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: jobCollectionName
        description: The job collection name
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The resource group name
      responses:
        200:
          description: OK
      tags:
      - Job Collections
    patch:
      summary: Job Collections Patch
      description: Patches an existing job collection.
      operationId: JobCollections_Patch
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftschedulerjobcollectionsjobcollectionname-patch
      parameters:
      - in: body
        name: jobCollection
        description: The job collection definition
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: jobCollectionName
        description: The job collection name
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The resource group name
      responses:
        200:
          description: OK
      tags:
      - Job Collections
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---