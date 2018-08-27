---
swagger: "2.0"
x-collection-name: moltin
x-complete: 0
info:
  title: Moltin API Create Products <=> Collections Relationships
  description: Here you can add `Collection`'s to a product. `Collection`'s specified
    in the payload willbe related to the product.
  version: 1.0.0
host: api.moltin.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v2/collections:
    get:
      summary: Get Collections List
      description: Get collections list.
      operationId: V2CollectionsGet
      x-api-path-slug: v2collections-get
      parameters:
      - in: header
        name: Accept
      - in: header
        name: Content-Type
      responses:
        200:
          description: Successful response
      tags:
      - Collections
      - List
  /v2/products/{productID}/relationships/collections:
    put:
      summary: Update Products <=> Collections Relationships
      description: '`Collection`''s specified in the payload willbe related to the
        product any relatiosnhips to `Collection`''s **NOT** specified in payload
        will be removed.'
      operationId: V2ProductsRelationshipsCollectionsByProductIDPut
      x-api-path-slug: v2productsproductidrelationshipscollections-put
      parameters:
      - in: header
        name: Accept
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      - in: path
        name: productID
      responses:
        200:
          description: Successful response
      tags:
      - Productss
      - Collections
      - Relationships
    post:
      summary: Create Products <=> Collections Relationships
      description: Here you can add `Collection`'s to a product. `Collection`'s specified
        in the payload willbe related to the product.
      operationId: V2ProductsRelationshipsCollectionsByProductIDPost
      x-api-path-slug: v2productsproductidrelationshipscollections-post
      parameters:
      - in: header
        name: Accept
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      - in: path
        name: productID
      responses:
        200:
          description: Successful response
      tags:
      - Productss
      - Collections
      - Relationships
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