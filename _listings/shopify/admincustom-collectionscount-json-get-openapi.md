---
swagger: "2.0"
x-collection-name: Shopify
x-complete: 0
info:
  title: Shopify Get a count of all custom collections
  description: Get a count of all custom collections.
  version: 1.0.0
host: DefaultParameterValue:DefaultParameterValue@DefaultParameterValue.myshopify.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /admin/custom_collections.json:
    get:
      summary: Get a list of all custom collections
      description: Get a list of all custom collections.
      operationId: getAdminCustomCollections.json
      x-api-path-slug: admincustom-collections-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - List
      - Custom
      - Collections
  /admin/custom_collections/246409795.json:
    get:
      summary: Get a single custom collections
      description: Get a single custom collections.
      operationId: getAdminCustomCollections246409795.json
      x-api-path-slug: admincustom-collections246409795-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Single
      - Custom
      - Collections
  /admin/smart_collections/count.json:
    get:
      summary: Get a count of all collections
      description: Get a count of all collections.
      operationId: getAdminSmartCollectionsCount.json
      x-api-path-slug: adminsmart-collectionscount-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Count
      - Collections
  /admin/custom_collections/count.json:
    get:
      summary: Get a count of all custom collections
      description: Get a count of all custom collections.
      operationId: getAdminCustomCollectionsCount.json
      x-api-path-slug: admincustom-collectionscount-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Count
      - Custom
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