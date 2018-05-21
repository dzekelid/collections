---
swagger: "2.0"
x-collection-name: Box
x-complete: 0
info:
  title: Box Get Collection Items
  description: "Retrieves the files and/or folders contained within this collection.
    Collection item lists behave a lot like getting a folder\u2019s items.\nPaginated
    results can be retrieved using the limit and offset parameters.\nSub-object fields
    can be requested via the ?fields parameter"
  version: 1.0.0
host: api.box.com
basePath: /2.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /collections:
    get:
      summary: Get Collections
      description: Retrieves the collections for the given user. Currently, only the
        favorites collection is supported.
      operationId: getCollections
      x-api-path-slug: collections-get
      responses:
        200:
          description: OK
      tags:
      - Documents
      - Collections
  /collections/{COLLECTION_ID}/items:
    get:
      summary: Get Collection Items
      description: "Retrieves the files and/or folders contained within this collection.
        Collection item lists behave a lot like getting a folder\u2019s items.\nPaginated
        results can be retrieved using the limit and offset parameters.\nSub-object
        fields can be requested via the ?fields parameter"
      operationId: getCollectionItems
      x-api-path-slug: collectionscollection-iditems-get
      parameters:
      - in: path
        name: COLLECTION_ID
      - in: query
        name: fields
        description: Attribute(s) to include in the response
      - in: query
        name: limit
        description: The maximum number of items to return in a page
      - in: query
        name: offset
        description: The offset at which to begin the response
      responses:
        200:
          description: OK
      tags:
      - Documents
      - Collections
      - Collection
      - ""
      - Items
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