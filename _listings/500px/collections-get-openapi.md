---
swagger: "2.0"
x-collection-name: 500px
x-complete: 0
info:
  title: 500px Get Collections
  description: Returns a listing of all Users collections and sets.
  version: v1
host: api.500px.com
basePath: /v1/
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
      description: Returns a listing of all Users collections and sets.
      operationId: getCollections
      x-api-path-slug: collections-get
      parameters:
      - in: query
        name: photos_per_collection_limit
        description: The number of photos included in each collection
      responses:
        200:
          description: OK
      tags:
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