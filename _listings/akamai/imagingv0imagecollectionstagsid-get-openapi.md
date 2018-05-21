---
swagger: "2.0"
x-collection-name: Akamai
x-complete: 0
info:
  title: Akamai API Get an Image Collection&#8217;s Tags
  description: Get an Image Collection&#8217;s Tags
  version: 1.0.0
host: developer.akamai.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /imaging/v0/imagecollections:
    get:
      summary: List Image Collections By Tag
      description: List Image Collections By Tag
      operationId: imagingv0imagecollectionstag
      x-api-path-slug: imagingv0imagecollections-get
      parameters:
      - in: query
        name: tag
        description: Image tag you want to match in a collection
        type: string
      responses:
        200:
          description: OK
      tags:
      - Imaging
      - V0
      - Imagecollections
      - Tag
  /imaging/v0/imagecollections/{id}:
    get:
      summary: Get an Image Collection
      description: Get an Image Collection
      operationId: imagingv0imagecollectionsid
      x-api-path-slug: imagingv0imagecollectionsid-get
      parameters:
      - in: query
        name: id
        description: 'Unique identifier for the image collection '
        type: string
      responses:
        200:
          description: OK
      tags:
      - Imaging
      - V0
      - Imagecollections
    put:
      summary: Add or Modify an Image Collection
      description: Add or Modify an Image Collection
      operationId: imagingv0imagecollectionsid
      x-api-path-slug: imagingv0imagecollectionsid-put
      parameters:
      - in: query
        name: id
        description: 'Unique identifier for the image collection '
        type: string
      responses:
        200:
          description: OK
      tags:
      - Imaging
      - V0
      - Imagecollections
  /imaging/v0/imagecollections/tags/{id}:
    get:
      summary: Get an Image Collection&#8217;s Tags
      description: Get an Image Collection&#8217;s Tags
      operationId: imagingv0imagecollectionstagsid
      x-api-path-slug: imagingv0imagecollectionstagsid-get
      parameters:
      - in: query
        name: id
        description: 'Unique identifier for the image collection '
        type: string
      responses:
        200:
          description: OK
      tags:
      - Imaging
      - V0
      - Imagecollections
      - Tags
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