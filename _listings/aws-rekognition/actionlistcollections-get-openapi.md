---
swagger: "2.0"
x-collection-name: AWS Rekognition
x-complete: 0
info:
  title: AWS Rekognition API List Collections
  version: 1.0.0
  description: Returns list of collection IDs in your account.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=CreateCollection:
    get:
      summary: Create Collection
      description: Creates a collection in an AWS Region.
      operationId: createCollection
      x-api-path-slug: actioncreatecollection-get
      parameters:
      - in: query
        name: CollectionId
        description: ID for the collection that you are creating
        type: string
      responses:
        200:
          description: OK
      tags:
      - Machine Learning
      - Collections
  /?Action=DeleteCollection:
    get:
      summary: Delete Collection
      description: Deletes the specified collection.
      operationId: deleteCollection
      x-api-path-slug: actiondeletecollection-get
      parameters:
      - in: query
        name: CollectionId
        description: ID of the collection to delete
        type: string
      responses:
        200:
          description: OK
      tags:
      - Machine Learning
      - Collections
  /?Action=ListCollections:
    get:
      summary: List Collections
      description: Returns list of collection IDs in your account.
      operationId: listCollections
      x-api-path-slug: actionlistcollections-get
      parameters:
      - in: query
        name: MaxResults
        description: Maximum number of collection IDs to return
        type: string
      - in: query
        name: NextToken
        description: Pagination token from the previous response
        type: string
      responses:
        200:
          description: OK
      tags:
      - Machine Learning
      - Collections
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