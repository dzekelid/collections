---
swagger: "2.0"
x-collection-name: BigOven
x-complete: 0
info:
  title: Big Oven Get the list of current, seasonal recipe collections. From here,
    you can use the /collection/{id} endpoint to retrieve the recipes in those collections.
  description: Get the list of current, seasonal recipe collections. from here, you
    can use the /collection/{id} endpoint to retrieve the recipes in those collections..
  termsOfService: Please see our [terms of service](http://api2.bigoven.com/web/documentation/termsofuse
  version: partner
host: api2.bigoven.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /collections:
    get:
      summary: Get the list of current, seasonal recipe collections. From here, you
        can use the /collection/{id} endpoint to retrieve the recipes in those collections.
      description: Get the list of current, seasonal recipe collections. from here,
        you can use the /collection/{id} endpoint to retrieve the recipes in those
        collections..
      operationId: Collection_Collections
      x-api-path-slug: collections-get
      parameters:
      - in: query
        name: test
      responses:
        200:
          description: OK
      tags:
      - Recipes
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