swagger: "2.0"
x-collection-name: Box
x-complete: 1
info:
  title: Box
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
      description: |-
        Retrieves the files and/or folders contained within this collection. Collection item lists behave a lot like getting a folder???s items.
        Paginated results can be retrieved using the limit and offset parameters.
        Sub-object fields can be requested via the ?fields parameter
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