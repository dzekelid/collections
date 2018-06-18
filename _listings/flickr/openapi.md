---
swagger: "2.0"
x-collection-name: Flickr
x-complete: 1
info:
  title: Flickr
  description: explore-upload-and-organize-photos-on-flickr
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
  /rest/?method=flickr.collections.getTree:
    get:
      summary: Collections Get Tree
      description: Returns a tree (or sub tree) of collections belonging to a given
        user.
      operationId: getRestMethodFlickr.collections.gettree
      x-api-path-slug: restmethodflickr-collections-gettree-get
      parameters:
      - in: query
        name: api_key
        description: Your API application key
      - in: query
        name: collection_id
        description: The ID of the collection to fetch a tree for, or zero to fetch
          the root collection
      - in: query
        name: format
        description: Response format
      - in: query
        name: user_id
        description: The ID of the account to fetch the collection tree for
      responses:
        200:
          description: OK
      tags:
      - Collections
      - GetTree
  /rest/?method=flickr.stats.getCollectionStats:
    get:
      summary: Stats Get Collection Stats
      description: Get the number of views on a collection for a given date.
      operationId: getRestMethodFlickr.stats.getcollectionstats
      x-api-path-slug: restmethodflickr-stats-getcollectionstats-get
      parameters:
      - in: query
        name: api_key
        description: Your API application key
      - in: query
        name: collection_id
        description: The id of the collection to get stats for
      - in: query
        name: date
        description: Stats will be returned for this date
      - in: query
        name: format
        description: Response format
      responses:
        200:
          description: OK
      tags:
      - Stats
      - GetCollectionStats
---