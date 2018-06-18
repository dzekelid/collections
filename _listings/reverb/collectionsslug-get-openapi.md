---
swagger: "2.0"
x-collection-name: Reverb
x-complete: 0
info:
  title: reverb Get Collections Slug
  description: Get collections slug.
  termsOfService: https://reverb.com/page/terms
  contact:
    name: Reverb API
    url: https://dev.reverb.com
    email: integrations@reverb.com
  version: "3.0"
host: api.reverb.com
basePath: /api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /my/follows/collections/{slug}:
    delete:
      summary: Delete My Follows Collections Slug
      description: Delete my follows collections slug.
      operationId: deleteMyFollowsCollectionsSlug
      x-api-path-slug: myfollowscollectionsslug-delete
      parameters:
      - in: path
        name: slug
      responses:
        200:
          description: OK
      tags:
      - My
      - Follows
      - Collections
      - Slug
    get:
      summary: Get My Follows Collections Slug
      description: Get my follows collections slug.
      operationId: getMyFollowsCollectionsSlug
      x-api-path-slug: myfollowscollectionsslug-get
      parameters:
      - in: path
        name: slug
      responses:
        200:
          description: OK
      tags:
      - My
      - Follows
      - Collections
      - Slug
    post:
      summary: Post My Follows Collections Slug
      description: Post my follows collections slug.
      operationId: postMyFollowsCollectionsSlug
      x-api-path-slug: myfollowscollectionsslug-post
      parameters:
      - in: path
        name: slug
      responses:
        200:
          description: OK
      tags:
      - My
      - Follows
      - Collections
      - Slug
  /collections:
    get:
      summary: Get Collections
      description: List of curated collections
      operationId: getCollections
      x-api-path-slug: collections-get
      responses:
        200:
          description: OK
      tags:
      - Collections
  /collections/{slug}:
    get:
      summary: Get Collections Slug
      description: Get collections slug.
      operationId: getCollectionsSlug
      x-api-path-slug: collectionsslug-get
      parameters:
      - in: path
        name: slug
      responses:
        200:
          description: OK
      tags:
      - Collections
      - Slug
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