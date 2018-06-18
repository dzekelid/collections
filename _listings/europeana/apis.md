---
name: Europeana
x-slug: europeana
description: Explore 51,990,182 artworks, artefacts, books, videos and sounds from
  more than 3,500 museums, galleries, libraries and archives across Europe.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/777-europeana.jpg
x-kinRank: "9"
x-alexaRank: "68066"
tags: Collections
created: "2018-06-18"
modified: "2018-06-18"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/collections/master/_listings/europeana/apis.md
specificationVersion: "0.14"
apis:
- name: Europeana get a single record in JSON format
  x-api-slug: europeana
  description: Get a single record in json format.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/777-europeana.jpg
  humanURL: http://europeana.eu/portal/
  baseURL: https://www.europeana.eu/v2///record/{collectionId}/{recordId}.json
  tags: Collections
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/collections/master/_listings/europeana/recordcollectionidrecordid-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/collections/master/_listings/europeana/recordcollectionidrecordid-json-get-openapi.md
- name: Europeana get single record in JSON LD format
  x-api-slug: europeana
  description: Get single record in json ld format.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/777-europeana.jpg
  humanURL: http://europeana.eu/portal/
  baseURL: https://www.europeana.eu/v2///record/{collectionId}/{recordId}.jsonld
  tags: Collections
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/collections/master/_listings/europeana/recordcollectionidrecordid-jsonld-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/collections/master/_listings/europeana/recordcollectionidrecordid-jsonld-get-openapi.md
- name: Europeana get single record in RDF format)
  x-api-slug: europeana
  description: Get single record in rdf format).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/777-europeana.jpg
  humanURL: http://europeana.eu/portal/
  baseURL: https://www.europeana.eu/v2///record/{collectionId}/{recordId}.rdf
  tags: Collections
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/collections/master/_listings/europeana/recordcollectionidrecordid-rdf-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/collections/master/_listings/europeana/recordcollectionidrecordid-rdf-get-openapi.md
- name: Europeana
  x-api-slug: europeana
  description: Explore 51,990,182 artworks, artefacts, books, videos and sounds from
    more than 3,500 museums, galleries, libraries and archives across Europe.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/777-europeana.jpg
  humanURL: http://europeana.eu/portal/
  baseURL: https://www.europeana.eu/v2/
  tags: Collections
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/collections/master/_listings/europeana/openapi.md
x-common:
- type: x-base
  url: http://www.europeana.eu/api/
- type: x-blog
  url: http://blog.europeana.eu/
- type: x-blog-rss
  url: http://blog.europeana.eu/feed/
- type: x-crunchbase
  url: https://crunchbase.com/organization/europeana
- type: x-developer
  url: http://europeana.eu/portal/api-introduction.html
- type: x-github
  url: https://github.com/europeana
- type: x-twitter
  url: https://twitter.com/EuropeanaEU
- type: x-website
  url: http://europeana.eu/portal/
- type: x-website
  url: http://europeana.eu
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---