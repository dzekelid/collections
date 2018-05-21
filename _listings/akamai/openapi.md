---
swagger: "2.0"
x-collection-name: Akamai
x-complete: 1
info:
  title: Akamai API
  description: the-akamai-api-for-managing-your-akamai-service
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
    put:
      summary: Modify an Image Collection&#8217;s Tags
      description: Modify an Image Collection&#8217;s Tags
      operationId: imagingv0imagecollectionstagsid
      x-api-path-slug: imagingv0imagecollectionstagsid-put
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
---