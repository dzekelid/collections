---
swagger: "2.0"
x-collection-name: Flickr
x-complete: 0
info:
  title: Flickr Collections Get Info
  description: Returns information for a single collection. Currently can only be
    called by the collection owner, this may change.
  version: 1.0.0
host: api.flickr.com
basePath: /services/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /rest/?method=flickr.collections.getInfo:
    get:
      summary: Collections Get Info
      description: Returns information for a single collection. Currently can only
        be called by the collection owner, this may change.
      operationId: getRestMethodFlickr.collections.getinfo
      x-api-path-slug: restmethodflickr-collections-getinfo-get
      parameters:
      - in: query
        name: api_key
        description: Your API application key
      - in: query
        name: collection_id
        description: The ID of the collection to fetch information for
      - in: query
        name: format
        description: Response format
      responses:
        200:
          description: OK
      tags:
      - Collections
      - GetInfo
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