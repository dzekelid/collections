swagger: "2.0"
x-collection-name: BlazeMeter
x-complete: 1
info:
  title: Blazemeter API Explorer
  description: live-api-documentation
  version: 1.0.0
host: a.blazemeter.com
basePath: /api/v4
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /user/collections:
    get:
      summary: Get User Collections
      description: Get user collections.
      operationId: retrieveCollections
      x-api-path-slug: usercollections-get
      parameters:
      - in: query
        name: limit
      - in: query
        name: skip
      responses:
        200:
          description: OK
      tags:
      - Monitoring
      - User
      - Collections