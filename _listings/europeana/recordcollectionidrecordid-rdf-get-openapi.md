---
swagger: "2.0"
x-collection-name: Europeana
x-complete: 0
info:
  title: Europeana get single record in RDF format)
  description: Get single record in rdf format).
  termsOfService: http://www.europeana.eu/portal/en/rights.html
  contact:
    name: http://labs.europeana.eu/api
  version: 1.0.0
host: www.europeana.eu
basePath: v2/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /record/{collectionId}/{recordId}.json:
    get:
      summary: get a single record in JSON format
      description: Get a single record in json format.
      operationId: getSingleRecordJson
      x-api-path-slug: recordcollectionidrecordid-json-get
      parameters:
      - in: query
        name: callback
        description: callback
      - in: path
        name: collectionId
        description: collectionId
      - in: query
        name: hierarchytimeout
        description: hierarchytimeout
      - in: query
        name: profile
        description: profile
      - in: path
        name: recordId
        description: recordId
      - in: query
        name: wskey
        description: wskey
      responses:
        200:
          description: OK
      tags:
      - Collections
  /record/{collectionId}/{recordId}.jsonld:
    get:
      summary: get single record in JSON LD format
      description: Get single record in json ld format.
      operationId: getSingleRecordJsonLD
      x-api-path-slug: recordcollectionidrecordid-jsonld-get
      parameters:
      - in: query
        name: callback
        description: callback
      - in: path
        name: collectionId
        description: collectionId
      - in: query
        name: format
        description: format
      - in: path
        name: recordId
        description: recordId
      - in: query
        name: wskey
        description: wskey
      responses:
        200:
          description: OK
      tags:
      - Collections
  /record/{collectionId}/{recordId}.rdf:
    get:
      summary: get single record in RDF format)
      description: Get single record in rdf format).
      operationId: getSingleRecordRDF
      x-api-path-slug: recordcollectionidrecordid-rdf-get
      parameters:
      - in: path
        name: collectionId
        description: collectionId
      - in: path
        name: recordId
        description: recordId
      - in: query
        name: wskey
        description: wskey
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