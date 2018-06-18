---
swagger: "2.0"
x-collection-name: 500px
x-complete: 1
info:
  title: 500px
  description: 500px-is-a-photo-community-powered-by-creative-people-worldwide-that-lets-you-discover-share-buy-and-sell-inspiring-photographs-
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
    post:
      summary: Post Collections
      description: Creates new a collection.
      operationId: postCollections
      x-api-path-slug: collections-post
      parameters:
      - in: query
        name: kind
        description: 'Kind of the Collection to be created Recognized values: 1 -
          Portfolio Set (default), 2 - Profile Set'
      - in: query
        name: path
        description: Path where the collection will be accessible at 500px
      - in: query
        name: path (required)
        description: Path where the collection will be accessible at 500px
      - in: query
        name: photo_ids
        description: Comma separated list of Photo ID values to post with the blog
      - in: query
        name: position
        description: Position of the collection in the list of collections
      - in: query
        name: title
        description: Title for the collection
      - in: query
        name: title (required)
        description: Title for the collection
      responses:
        200:
          description: OK
      tags:
      - Collections
  /collections/:id:
    delete:
      summary: Delete Collections
      description: Deletes collection.
      operationId: deleteCollections
      x-api-path-slug: collectionsid-delete
      parameters:
      - in: query
        name: Forkn      n      n        69
      - in: query
        name: Starn  nn    n      281
      responses:
        200:
          description: OK
      tags:
      - Collections
    get:
      summary: Get Collections
      description: Returns a collection.
      operationId: getCollections
      x-api-path-slug: collectionsid-get
      parameters:
      - in: query
        name: image_size - Numerical size of the image to link to, 1 being the smallest
          and 4 being the largest. Multiple image sizes may be specified as image_size[]=2&amp;image_size[]=4.
      responses:
        200:
          description: OK
      tags:
      - Collections
    put:
      summary: Put Collections
      description: Updates collection.
      operationId: putCollections
      x-api-path-slug: collectionsid-put
      parameters:
      - in: query
        name: id (required)
        description: Collection ID
      - in: query
        name: kind
        description: Change kind of the Collection
      - in: query
        name: path
        description: Path where the collection will be accessible at 500px
      - in: query
        name: photo_ids
        description: Comma separated list of Photo ID values that are in this collection
      - in: query
        name: position
        description: Position of the collection in the list of collections
      - in: query
        name: title
        description: Title for the collection
      responses:
        200:
          description: OK
      tags:
      - Collections
  /collections/{id}:
    get:
      summary: Get Collections
      description: Returns the collection.
      operationId: getCollections
      x-api-path-slug: collectionsid-get
      parameters:
      - in: path
        name: id
        description: Collection (set) ID
      responses:
        200:
          description: OK
      tags:
      - Collections
    put:
      summary: Put Collections
      description: Updates collection.
      operationId: putCollections
      x-api-path-slug: collectionsid-put
      parameters:
      - in: path
        name: id
        description: The Collection (set) ID
      - in: query
        name: kind
        description: 'Kind of the Collection to be created Recognized values: 1 -
          Portfolio Set (default), 2 - Profile Set'
      - in: query
        name: path
        description: Path where the collection (set) will be accessible at 500px
      - in: query
        name: photo_ids
        description: Comma separated list of Photo ID values
      - in: query
        name: position
        description: Position of the collection in the list of collections
      - in: query
        name: title
        description: Title for the collection (set)
      responses:
        200:
          description: OK
      tags:
      - Collections
    delete:
      summary: Delete Collections
      description: Deletes the collection.
      operationId: deleteCollections
      x-api-path-slug: collectionsid-delete
      parameters:
      - in: path
        name: id
        description: Collection (set) ID to delete
      responses:
        200:
          description: OK
      tags:
      - Collections
---